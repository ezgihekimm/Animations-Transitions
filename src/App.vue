<template>
  <div>

    <menu1 />
    <introduction />
    <technicial />
    <usage />
    <resim/>

  



   

  

    
 

    <section data-bs-version="5" class="footer1 cid-sCnnvd6rsP" once="footers" id="footer1-a">





      <div class="container">
        <div class="row">
          <div class="col-12 col-md-12 col-lg-7">
            <h4 class="mbr-section-subtitle ls-2 mbr-fonts-style display-4">
              USEFUL LINKS
            </h4>
            <ul class="foot-menu">





              <li class="foot-menu-item mbr-fonts-style display-7">
                <a class="text-warning" href="index.html#features9-3">About us</a>
              </li>
              <li class="foot-menu-item mbr-fonts-style display-7">
                <a class="text-warning" href="index.html#features7-7">Services</a>
              </li>
              <li class="foot-menu-item mbr-fonts-style display-7">
                <a class="text-warning" href="index.html#form2-8">Contact Us</a>
              </li>
              <li class="foot-menu-item mbr-fonts-style display-7"><a href="index.html#features8-5"
                  class="text-warning">Works</a></li>
            </ul>
          </div>
          <div class="col-12 col-md-12 col-lg-5">
            <div class="box">
              <h4 class="mbr-section-subtitle ls-2 mbr-fonts-style display-4">
                LET'S TALK
              </h4>
              <ul class="foot-contacts">


                <li class="foot-phone mbr-fonts-style display-7">
                  <a class="text-warning" href="#">1234 567 890</a>
                </li>
                <li class="foot-mail mbr-fonts-style display-7">
                  <a class="text-warning" href="#">mobirise@company.com</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <balon />
  </div>

</template>

<script>
  import 'animate.css'
  import menu1 from './components/menu1.vue'
  import introduction from './components/introduction.vue'
  import technicial from './components/technicial.vue'
  import balon from './components/balon.vue'
  import usage from './components/usage.vue'
  import resim from './components/resim.vue'
  export default {
    name: 'App',
    components: {
      menu1,
      introduction,
      technicial,
      balon,
      usage,
      resim

    }

  }
</script>

<style>

</style>