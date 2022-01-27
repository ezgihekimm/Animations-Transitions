<template>

    <div class="sticky-container">
        <div class="container-fluid">
            <div class="main_header">
                <div class="row justify-content-center">
                    <div class="col-12 col-md-12 col-lg-12 align-center">

                        <h5 class="mbr-section-title mb-5 mt-o mbr-fonts-style ls-1 display-2 "
                            style="font-family: 'Roboto', sans-serif; color:#C4E5F6">
                            3D APPEARANCE</h5>

                    </div>
                </div>
            </div>
        </div>

        <div class="sticky d-flex">
         
            <div class="container mt-5">
                <div class="list col-md-12 d-flex justify-content-end mt-5 ">
                    <ul id="spec" class="animate__animated animate__bounce">
                        <li>
                            <h3>Depth : 60 m (IP68)</h3>
                        </li>
                        <li>
                            <h3>Luminous Flux <h3 style="display:inline">: 800-1400 Im</h3>
                            </h3>
                        </li>
                        <li>
                            <h3>Operation Time : 5 Hours (With 2 hours charge)</h3>
                        </li>
                        <li>
                            <h3>Montage : Handheld</h3>
                        </li>
                        <li>
                            <h3>Power : 9.000 mAh</h3>
                        </li>
                        <li>
                            <h3>Weight : 1,5 Kg</h3>
                        </li>
                        <li>
                            <h3>Storage : -5 C°/ +45 C° </h3>
                        </li>
                    </ul>
                </div>
            </div>
            <div id="animation-container">

            </div>
        </div>


    </div>
</template>

<script>
    export default {}
</script>

<style>
    .sticky-container {
        background-color: #121212;
        height: 1800px;
    }

    .sticky {
        position: sticky;
        top: 50px;

    }

    #animation-container {
        height: 844px;
    }

    #spec h3{
        font-size: 20px;
        font-weight: 100;
        color:white;
        font-family: 'Roboto', sans-serif;
    }
    #spec li{
        line-height: 50px;
    }
</style>