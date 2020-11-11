<template>
  <section>
      <nav class="navbar navbar-expand-lg navbar-dark bg-info fixed-top" id="sideNav">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">
          <span class="d-block d-lg-none">Resume Yana</span>
          <span class="d-none d-lg-block">
            <img class="img-fluid img-profile rounded-circle mx-auto mb-2" src="/profile.jpg" alt="">
          </span>
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#about">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#experience">Pengalaman</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#education">Pendidikan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#skills">Keterampilan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#interests">Minat</a>
            </li>
            <!-- <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#awards">Awards</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="/gallery">Portfolio</a>
            </li> -->
          </ul>
        </div>
      </nav>

      <div class="resume">
          <Resume />
      </div>
  </section>
</template>

<script>
import Resume from "@/components/Resume"

export default {
    components: {
        Resume
    }
}
</script>

<style scoped>
/* @media (min-width:992px){
  body{padding-top:0;padding-left:17rem}
  } */
  h1 {
    font-size: 3rem;
    line-height: 5.5rem;
  }
  @media (min-width:992px){
      .resume {
        padding-top:0;
        padding-left:17rem;
      }
  }
</style>
