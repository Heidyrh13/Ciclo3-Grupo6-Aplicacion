<template>
  <div class="home">
    <!-- About -->
    <section class="bg-about text-white text-center" id="about">
        <div class="container px-5">
            <div class="row gx-5 align-items-center justify-content-center justify-content-lg-between">
                <div class="col-12 col-lg-5 col-md-6">
                    <h2 class="display-4 lh-1 mb-4 text-title">ABOUT US</h2>
                    <p class="lead fw-normal text-muted mb-5 mb-lg-0">Nacimos como una empresa que quiere darle a los Colombianos una alternativa de vuelos más seguro y con mejores precios.</p>
                    <br/>
                    <p class="lead fw-normal text-muted mb-5 mb-lg-0">Más que vender vuelos, vendemos sueños. Volar es una manera de liberarse, encontrarse y disfrutar de una nueva aventura.</p>
                    <a class="btn btn-outline-light btn-social mx-1 mt-5" href="#!"><i class="fab fa-fw fa-facebook-f"></i></a>
                    <a class="btn btn-outline-light btn-social mx-1 mt-5" href="#!"><i class="fab fa-fw fa-twitter"></i></a>
                    <a class="btn btn-outline-light btn-social mx-1 mt-5" href="#!"><i class="fab fa-fw fa-linkedin-in"></i></a>
                    <a class="btn btn-outline-light btn-social mx-1 mt-5" href="#!"><i class="fab fa-fw fa-dribbble"></i></a>
                
                </div>                
                <div class="col-sm-8 col-md-6">
                    <div class="px-5 px-sm-0">
                        <img class="img-fluid rounded-circle" src="../assets/img/background/About_WA-05.png" alt="Imagen de personas"/>
                    </div>
                </div>               
            </div>
        </div>
    </section> 
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Footer
  }
}
</script>

