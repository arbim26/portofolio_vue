<script setup>
  import {
    RouterLink,
    RouterView
  } from "vue-router";
  import HelloWorld from "./components/HelloWorld.vue";
  import Instagram from "./components/icons/Instagram.vue";
  import Github from "./components/icons/Github.vue";
  import Linkedin from "./components/icons/Linkedin.vue";
  import Phone from "./components/icons/Phone.vue";
  import Instagram1 from "./components/icons/Instagram.vue";
  import HTML from "./components/icons/HTML.vue";
  import CSS from "./components/icons/CSS.vue";
  import JS from "./components/icons/JS.vue";
  import PHP from "./components/icons/PHP.vue";
  import Figma from "./components/icons/Figma.vue";
</script>

<template>
  <div class="awal">
    <!-- Nvabar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
      <div class="container">
        <a class="navbar-brand font-weight-bold" href="#">ARBIM</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#">HOME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">ABOUT</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">PORTOFOLIO</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- End Nav -->

    <!-- HERO IMAGE -->
    <section id="hero">
      <div class="container">
        <div class="text-center pt-5">
          <img src="@/assets/arbim.jpeg" class="" style="height: 175px; border-radius: 200px" alt="..." />
        </div>

        <h1 class="mt-3 text-center putih">
          ARYA BIMA <br />
          SETYONO
        </h1>

        <h5 class="mt-5 text-center putih">I'am a Frontend Developer</h5>

        <div class="text-center mt-5 kontak">
          <Instagram />
          <Github />
          <Linkedin />
          <Phone />
        </div>

        <div class="text-center mt-5 pb-5">
          <button type="button" class="btn putih btn-info">See About Me</button>
        </div>
      </div>
    </section>
    <!-- Main -->

    <!-- about -->
    <div id="About">
      <div class="container ">
        <h3 class="text-center putih mt-2">About Me</h3>

        <div class="card ">
          <div class="row">
            <div class="col p-5">
              <h3 class="putih text-center pb-3">Profile</h3>
              <div class="text-center ">
                <img src="@/assets/arbim.jpeg" class="mb-3" style="height: 120px; border-radius: 200px" alt="..." />
              </div>
              <p class="putih pe  ">I was born in Nganjuk, June 26, 2005. I am currently studying at SMK Taruna Bhakti,
                Depok, with a degree in software engineering. I have the expertise to design a web layout and have
                skills the HTML, CSS and JavaScript programming languages. I can work in a team and have the ability to
                speak in public.</p>
            </div>
            <div class="col d-flex gap-3 p-5 flex-md-column">
              <h3 class="text-center putih">Skills</h3>

              <div class="row">
                <div class="col-2">
                  <HTML href="https://www.instagram.com/arbiiim/" />
                </div>
                <div class="col">
                  <label class="putih">HTML</label>
                  <div class="progress">
                    <div class="progress-bar bg-info" role="progressbar" style="width: 85%;" aria-valuenow="85"
                      aria-valuemin="0" aria-valuemax="100">85%</div>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-2">
                  <CSS />
                </div>
                <div class="col">
                  <label class="putih">CSS</label>
                  <div class="progress">
                    <div class="progress-bar bg-info" role="progressbar" style="width: 85%;" aria-valuenow="85"
                      aria-valuemin="0" aria-valuemax="100">85%</div>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-2">
                  <JS />
                </div>
                <div class="col">
                  <label class="putih">JavaScript</label>
                  <div class="progress">
                    <div class="progress-bar bg-info" role="progressbar" style="width: 40%;" aria-valuenow="40"
                      aria-valuemin="0" aria-valuemax="100">40%</div>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-2">
                  <PHP />
                </div>
                <div class="col">
                  <label class="putih">PHP</label>
                  <div class="progress">
                    <div class="progress-bar bg-info" role="progressbar" style="width: 40%;" aria-valuenow="40"
                      aria-valuemin="0" aria-valuemax="100">40%</div>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-2">
                  <Figma />
                </div>
                <div class="col">
                  <label class="putih">FIGMA</label>
                  <div class="progress">
                    <div class="progress-bar bg-info" role="progressbar" style="width: 90%;" aria-valuenow="90"
                      aria-valuemin="0" aria-valuemax="100">90%</div>
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>
    
      </div>
    </div>
    <!-- about -->

    <!-- Portofolio -->
    <section id="portofolio ">
      <div class="container mt-5">

        <h3 class="text-center putih mt-2">Portofolio</h3>

        <div class="d-flex justify-content-between">

          <div class="card" style="width: 18rem;">
            <img src="@/assets/Rosalia Indah.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <p class="card-text text-center putih">Redesign www.rosalia-indah.co.id</p>
            </div>
          </div>
  
          <div class="card" style="width: 18rem;">
            <img src="@/assets/Versi Arbim (1).jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <p class="card-text text-center putih">Travel Website Concept</p>
            </div>
          </div>
  
          <div class="card" style="width: 18rem;">
            <img src="@/assets/berger.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <p class="card-text text-center putih">Responsive Food Delevery Website Design</p>
            </div>

        </div>
        </div>
      </div>
    </section>


      <!-- FOOTER -->
    <section id="footer">
      <div class="container text-center p-5 text-white">
          <h6>2022 © arbim</h6>
      </div>

    </section>
    <!-- END FOOTER -->

  </div>
</template>

<style scoped>
  .pe {
    text-align: justify;
    font-size: larger;
  }

  .awal {
    background-color: #548CA8;
  }


  .putih {
    color: white;
  }

  .kotak {
    gap: 3px;
  }

  .card {
    background-color: #334257;
    margin-top: 30px;
  }
</style>