<template>
  <div class="container">
    <div class="row justify-content-center align-items-center">
      <div class="col-md-6 col-md-offset-3">
        <h3>Animation ve Transition</h3>
        <hr>
        <button type="button" class="btn btn-primary mb-5" @click="show = !show">Göster/Gizle</button>

        <transition name="fade">

          <div class="alert alert-success" v-if="show" role="alert">
            <h4 class="alert-heading">Well done!</h4>
            <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit
              longer so that you can see how spacing within an alert works with this kind of content.</p>
            <hr>
            <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
          </div>

        </transition>
        <hr>

        <transition name="slide">

          <div class="alert alert-warning" role="alert" v-if="show">
            A simple warning alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
          </div>
        </transition>

      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App',

    data() {
      return {
        show: false
      }
    }
  }
</script>

<style>
  .fade-enter {
    opacity: 0;

  }

  .fade-enter-active {
    transition: opacity 1s;


  }

  .fade-leave {
    /* opacity:1;*/
  }

  .fade-leave-active {
    transition: opacity 3s;
    opacity: 0;

  }
  
  .slide-enter{

  }
.slide-enter-active{
  animation: slide-in 1s ease-out forwards;

}
.slide-leave{

}
.slide-leave-active{
  animation: slide-out 3s ease-out forwards;

}

@keyframes slide-in {
  from{
    transform: translateY(20px);
  }
  to{
    transform: translateY(0px);
  }
}
  @keyframes slide-out {
    from{
      transform: translateY(0px);
    }
    to{
      transform: translateY(20px);
    }    
  }
</style>