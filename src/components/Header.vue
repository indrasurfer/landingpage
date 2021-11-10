<template>
<div clas="">
   <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
            <div class="container">
                <a class="navbar-brand" href="#page-top"><img src="../assets/images/logo1.png" alt="..." /></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                    Menu
                    <i class="fas fa-bars ms-1"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <ul class="navbar-nav text-uppercase ms-auto py-6 py-lg-0">
                        <li class="nav-item"><a class="nav-link" href="#services">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#portfolio">Features</a></li>
                        <li class="nav-item"><a class="nav-link" href="#about">Pricing</a></li>
                        <li class="nav-item"><a class="nav-link" href="#team">Team</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Screens</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">News</a></li>
                    </ul>
                </div>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <a class="btn btn-primary btn-xl text-uppercase ms-auto py-6 py-lg-0 button-download-bg button-download" href="#services">
                      <span>Download App</span>
                    </a>
                    
                </div>
            </div>
        </nav>
        <Banner/> 
</div>
</template>

<script>
import Banner from "@/components/Banner.vue";
export default {
  name: "Header",
  props: {
    msg: String,
  },
   components: {
    Banner,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

