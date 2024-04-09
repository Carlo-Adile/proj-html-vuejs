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

    <!-- seconda sezione: artist coaching -->
    <section id="my_second_section" class="py-4">
      <div class="my_container_sm">
        <div class="row debug">
          <div class="col-12 mb-0">
            <h3>Artist coaching</h3>
            <h4>I understand what it takes to create.</h4>
            <h4>I can help you with</h4>
          </div>
          <div class="col-3">
            <img src="../assets/images/artist-box-image-01.png" alt="">
            <h5>Online Courses</h5>
            <p>Online art coaching now offers you a very powerful way to redesign your artist mind.</p>
          </div>
          <div class="col-3">
            <img src="../assets/images/artist-box-image-02.png" alt="">
            <h5>One to One</h5>
            <p>Getting the necessary clarity about the current state to help you improve your ability.</p>
          </div>
          <div class="col-3">
            <img src="../assets/images/artist-box-image-03.png" alt="">
            <h5>Anywhere</h5>
            <p>Access to valuable and portable program which allow you to setup and live anywhere you want.</p>
          </div>
          <div class="col-3">
            <img src="../assets/images/artist-box-image-04.png" alt="">
            <h5>On Time</h5>
            <p>Punctuality is our priority because it's an essential criteria to access a program quality.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- terza sezione: caption+bio & video -->
    <section id="my_third_section">
      <div class="my_container_sm">
        <div class="row debug">
          <div class="col-4">
            <h2>I coach and mentor visual artists, like you, to Create like You Mean It</h2>
            <h4>Martin Garrix</h4>
          </div>
          <div class="col-8">
            <p>As a coach and mentor, my ultimate goal is to motivate visual artists towards inspired actions. I help
              you get you back on track to being the productive, creative, meaningful and authentic artist you truly
              want to be. I support artists in crafting and living a creative life as well as feeling good about
              themselves and their art.</p>
            <p>As an artist and educator for nearly 30 years, I understand what it takes to create.</p>
            <a class="btn btn-primary" href="#" role="button">Get started today</a>
          </div>
          <!-- video -->
          <div class="col-10 align-self-center border-1 py-4">
            <div id="my_video">
              <a href="#">
                <img src="../assets/images/icon-youtube-play.png" alt="">
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- quarta sezione: testimonials -->
    <section id="my_forth_section" class="py-4">
      <div class="my_container_xxl">
        <div class="row debug">
          <div class="col-12">
            <h3>Testimonials</h3>
            <h4>Why do people love me?</h4>
          </div>
          <div class="col-4">
            <div class="card">
              <h5>It's a choice of quality for people with special needs</h5>
              <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make
                things right and shine. Maxchoach guys just got me.</p>
              <div>
                <img src="" alt="">
                <h5>Florence Thomas</h5>
                <p>/ Multimedia Admin</p>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <h5>It's a choice of quality for people with special needs</h5>
              <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make
                things right and shine. Maxchoach guys just got me.</p>
              <div>
                <img src="" alt="">
                <h5>Florence Thomas</h5>
                <p>/ Multimedia Admin</p>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <h5>It's a choice of quality for people with special needs</h5>
              <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make
                things right and shine. Maxchoach guys just got me.</p>
              <div>
                <img src="" alt="">
                <h5>Florence Thomas</h5>
                <p>/ Multimedia Admin</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- quinta sezione: artist coaching -->
    <section id="my_fifth_section" class="py-4">
      <div class="my_container_xl">
        <div class="row debug">
          <div class="col-12 my-4">
            <h3>Artist coaching</h3>
            <h4>Latest Online Courses</h4>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 rounded-0 mb-3">
              <img src="../assets/images/artist-course-08-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-07-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-06-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-05-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-04-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-03-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-02-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 mb-3">
              <img src="../assets/images/artist-course-01-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <span>$18.00</span>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <!-- button -->
          <div class="col-12">
            <a class="btn btn-primary" href="#" role="button">View all courses</a>
          </div>
        </div>
      </div>

    </section>

    <!-- sesta sezione: lets work together -->
    <section id="my_sixth_section" class="py-4">
      <div class="my_container_sm">
        <div class="row debug">
          <div class="col-12">
            <h2>Upcoming Events</h2>
            <h4>Let's Work Together</h4>
          </div>
          <div class="col-6 mb-4 debug"></div>
          <div class="col-6 mb-4 debug"></div>
          <div class="col-6 debug"></div>
          <div class="col-6 debug"></div>
        </div>
      </div>
    </section>

    <!-- settima sezione: newsletter -->
    <section id="my_seventh_section" class="py-4">
      <div class="my_container_sm">
        <div class="row debug">
          <div class="col-4">
            <h4>Newsletter to get in touch</h4>
          </div>
          <div class="col-8">
            <span>Your e-mail</span>
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

.my_container_sm {
  @include mixin_container_sm;
}

.my_container_xl {
  @include mixin_container_xl;
}

.my_container_xxl {
  @include mixin_container_xxl;
}

#my_first_section {
  width: 100%;
  background-color: $primary;

  .row {
    height: 500px;
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

  #my_pics_right {
    position: relative;
    height: 100%;
    width: 100%;

    :nth-child(1) {
      position: absolute;
      bottom: 0;
      left: 0;
    }
  }
}

#my_second_section {
  .row {
    height: 400px;
  }
}

#my_third_section {
  .row {
    height: 700px;
  }

  #my_video {
    width: 100%;
    height: 400px;
    display: flex;
    align-items: center;
    /* bg video */
    background-image: url('../src/assets/images/artist-video-poster.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
}

#my_forth_section {
  .row {
    height: 500px;
  }
}

#my_fifth_section {
  .row {
    /* height: 600px; */
  }

  .card {
    img {
      border: none;
      border-radius: 0;
    }
  }
}

#my_sixth_section {
  .row {
    height: 600px;
  }

  .col-6 {
    height: 45%;
  }

}

#my_seventh_section {
  .row {
    height: 200px;
  }

}
</style>