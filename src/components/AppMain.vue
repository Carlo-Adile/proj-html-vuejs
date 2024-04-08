<script>
export default {
  name: "AppMain",
  data() {
    return {}
  }
}
</script>

<template>
  <div id="app_main">
    <!-- prima sezione: presentazione -->
    <section id="my_first_section" class="py-4">
      <div class="my_container_xl debug">
        <div class="row align-items-center px-4">
          <!-- left: pic showcase -->
          <div class="my_col_sm debug" id="my_pics_left">
            <div>
              <img src="../assets/images/artist-hero-image-02-232x300.jpg" alt="">
            </div>
            <div>
              <img src="../assets/images/artist-hero-image-01.jpg" alt="">
            </div>
          </div>
          <!-- center: small bio -->
          <div class="my_col_md debug">
            <h3>Hello, I'm Martin</h3>
            <h4>Artist Coaching And Mentoring</h4>
            <h4>Might Be for You.</h4>
            <a class="btn btn-primary" href="#" role="button">Get ticket</a>
          </div>
          <!-- right: pic personale -->
          <div class="my_col_sm debug" id="my_pics_right">
            <div>
              <img src="../assets/images/artist-hero-image-04-235x300.jpg" alt="">
            </div>
          </div>
        </div>
      </div>

    </section>

  </div>
</template>

<style lang="scss" scoped>
@import '../assets/scss/colors.scss';
@import '../assets/scss/structure.scss';

* {
  margin: 0 auto;
  text-align: center;
}

.debug {
  border: 1px dashed black;
}

#app_main {
  width: 100%;
}

#my_first_section {
  width: 100%;
  background-color: $primary;

  .my_container_xl {
    @include mixin_container_xl;

    .row {
      height: 500px;
    }
  }

  .my_col_sm {
    flex-basis: 30%;
    height: 80%;
  }

  .my_col_md {
    flex-basis: 40%;
  }

  #my_pics_left {
    position: relative;
    height: 100%;
    width: 100%;

    /* l'immagine 2 è stata concatenata alla immagine 1 per assicurare la sovrapposizione desiderata.
    immagine 1 mantiene risoluzione del file originale;
    immagine 2 80% grandezza del file originale. */
    :nth-child(1) {
      position: absolute;
      top: 0;
      right: 0;
      z-index: 1;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
      height: 300px;
      width: 232px;

      img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        position: relative;
      }
    }

    :nth-child(2) {
      position: absolute;
      bottom: 15px;
      left: 10px;
      z-index: 2;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
      height: 200px;
      width: 155px;

      img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
    }
  }

  #my_pics_right{
    position: relative;
    height: 100%;
    width: 100%;

    :nth-child(1){
      position: absolute;
      bottom: 0;
      left: 0;
    }
  }
}
</style>