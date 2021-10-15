<template>
  <div class="home">
    <!-- Masthead-->
    <header class="masthead bg-primary text-white text-center" id="home">
        <div class="container px-5">
            <div class="row gx-5 align-items-center justify-content-center justify-content-lg-between">
                <div class="col-12 col-lg-5 col-md-6">
                    <h2 class="display-5 lh-1 mb-5 text-title">Plan your next vacation!</h2>
                    <p class="lead fw-normal text-muted mb-5 mb-lg-0">Viaja con nosotros y haz parte de esta gran aventura llamada WolkenAir.</p>
                    <v-row>
                      <v-col class="col-12 col-lg-5 col-md-6">
                        <router-link to="/login">Login</router-link>
                      </v-col>
                      <v-col class="col-12 col-lg-5 col-md-6">
                        <router-link to="/register">Register</router-link>
                      </v-col>
                    </v-row>


                </div>                
                <div class="col-sm-6 col-md-6">
                    <img class="img-fluid rounded-circle" src="../assets/img/background/avion_home-02.png" alt="Imagen de un avión"/>
                </div>               
            </div>
        </div>
    </header>
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <Carroussel/>
    <Services/>
    <News/>
    <PortfolioTeam/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import PortfolioTeam from '@/components/PortfolioTeam.vue'
import Footer from '@/components/Footer.vue'
import News from '@/components/News.vue'
import Services from '@/components/Services.vue'
import Carroussel from '../components/Carroussel.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Carroussel,
    Services,
    News,
    PortfolioTeam,
    Footer
  }
  
}
</script>
