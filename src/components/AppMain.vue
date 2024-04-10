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
    <section id="my_first_section" class="my-4 py-4">
      <div id="bg_clip_left"></div>
      <div id="bg_clip_right"></div>
      <div id="my_buttons">
        <ul>
          <li><i class="fa-solid fa-ruler"></i></li>
          <li><i class="fa-regular fa-life-ring"></i></li>
          <li><i class="fa-solid fa-book"></i></li>
          <li><i class="fa-solid fa-cart-shopping"></i></li>
        </ul>
      </div>
      <div class="my_container_xl debug">
        <div class="row align-items-center px-4 my-4">
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
            <h1>Hello, I'm Martin</h1>
            <h3>Artist Coaching And Mentoring</h3>
            <h3 class="mb-2">Might Be for You.</h3>
            <a class="btn my-4" href="#" role="button">
              <p>Get started today</p>
            </a>
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
    <section id="my_second_section" class="my-4 py-4">
       <div class="my_container_sm">
        <div class="row debug">
          <div class="col-12 mb-4">
            <h1>Artist coaching</h1>
            <h4>I understand what it takes to create.</h4>
            <h4>I can help you with</h4>
          </div>
          <div class="col-3 align-self-end my-2 pb-4">
            <img src="../assets/images/artist-box-image-01.png" alt="">
            <h5>Online Courses</h5>
            <p>Online art coaching now offers you a very powerful way to redesign your artist mind.</p>
          </div>
          <div class="col-3 align-self-end pb-0">
            <img src="../assets/images/artist-box-image-02.png" alt="">
            <h5>One to One</h5>
            <p>Getting the necessary clarity about the current state to help you improve your ability.</p>
          </div>
          <div class="col-3 align-self-end pb-4">
            <img src="../assets/images/artist-box-image-03.png" alt="">
            <h5>Anywhere</h5>
            <p>Access to valuable and portable program which allow you to setup and live anywhere you want.</p>
          </div>
          <div class="col-3 align-self-end pb-0">
            <img src="../assets/images/artist-box-image-04.png" alt="">
            <h5>On Time</h5>
            <p>Punctuality is our priority because it's an essential criteria to access a program quality.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- terza sezione: caption+bio & video -->
    <section id="my_third_section" class="my-4 py-4">
      <div class="wave_bg"></div>
      <div class="my_container_sm">
        <div class="row debug">
          <div class="col-4">
            <img src="../assets/images/artist-quote-icon.png" alt="" style="width:30px; height:24px">
            <h3>I coach and mentor visual artists, like you, to Create like You Mean It</h3>
            <h1>Martin Garrix</h1>
          </div>
          <div class="col-6 mb-4" style="padding-top: 2rem;">
            <p style="text-align: left;">As a coach and mentor, my ultimate goal is to motivate visual artists towards
              inspired actions. I help
              you get you back on track to being the productive, creative, meaningful and authentic artist you truly
              want to be. I support artists in crafting and living a creative life as well as feeling good about
              themselves and their art.</p>
            <br>
            <p style="text-align: left;" class="mb-4">As an artist and educator for nearly 30 years, I understand what
              it takes to create.</p>
            <a class="btn" href="#" role="button">Get started today</a>
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
    <section id="my_forth_section" class="my-4 py-4">

      <div class="my_container_xxl">
        <div class="row debug">
          <div class="col-12">
            <h1>Testimonials</h1>
            <h3>Why do people love me?</h3>
          </div>
          <div class="col-4">
            <div class="card inactive">
              <h5>It's a choice of quality for people with special needs</h5>
              <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make
                things right and shine. Maxchoach guys just got me.</p>
              <div class="my_info">
                <img src="../assets/images/artist-testimonial-avatar-02.jpg" alt="">
                <h5>Florence Themes</h5>
                <p>/ Multimedia Admin</p>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <h5>High level of efficiency and scientific teaching methods</h5>
              <p>I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from
                the syllabus. Great study portal for people like me.</p>
              <div class="my_info">
                <img src="../assets/images/artist-testimonial-avatar-04.jpg" alt="">
                <h5>Mina Hollace</h5>
                <p>/ Freelancer</p>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card inactive">
              <div>
                <h5>It's a choice of quality for people with special needs</h5>
                <p>I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors
                  are smart and professional when dealing with students.</p>
              </div>
              <div class="my_info">
                <img src="../assets/images/artist-testimonial-avatar-01.jpg" alt="">
                <h5>Madley Pendor</h5>
                <p>/ IT Specialist</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- quinta sezione: artist coaching con cards -->
    <section id="my_fifth_section" class="my-4 py-4">
      <div class="my_container_xl">
        <div class="row debug">
          <div class="col-12 my-4">
            <h1>Artist coaching</h1>
            <h3>Latest Online Courses</h3>
          </div>
          <div class="col-3">
            <!-- card del corso -->
            <div class="card border-0 rounded-0 mb-3">
              <img src="../assets/images/artist-course-08-480x480.jpg" alt="" class="card-img">
              <div class="card-body">
                <p>$18.00</p>
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
                <p>$18.00</p>
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
                <p>$18.00</p>
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
                <p>$18.00</p>
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
                <p>$18.00</p>
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
                <p>$18.00</p>
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
                <p>$18.00</p>
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
                <p>$18.00</p>
                <h5>The Acrylic Painting Academy</h5>
                <span><i class="fa-regular fa-file-lines"></i> 4 Lessons </span>
                <span><i class="fa-regular fa-user"></i> 50 Students </span>
              </div>
            </div>
          </div>
          <!-- button -->
          <div class="col-12 d-flex justify-content-center my-4">
            <a class="btn" href="#" role="button">View all courses</a>
          </div>
        </div>
      </div>
    </section>

    <!--  !!!!!!!!!!!!!!
      sesta sezione: artist and tips -->
    <section id="my_sixth_section" class="my-4 py-4">
      <div class="my_container_md">
        <div class="row debug">
          <!-- header -->
          <div class="col-12 my-4">
            <h1>Artists and Tips</h1>
            <h3>Latest From The Blog</h3>
          </div>
          <!-- left -->
          <div class="col-3" id="my_left_card">
            <div class="card border-0 rounded-0">
              <img src="../assets/images/120084500_197897808368764_8114555493043279565_n.jpg" alt="" class="card-img">
              <div class="card-body my-2">
                <p>ARTIST</p>
                <h5>Brush Strokes Energize Trees Paintings</h5>
                <span><i class="fa-regular fa-calendar"></i> May 15, 2020</span>
                <span><i class="fa-regular fa-eye"></i> 688 views</span>
              </div>
            </div>
          </div>
          <!-- center -->
          <div class="col-6">
            <div class="card" id="my_center_card">
              <div id="my_center_text">
                <p>ARTIST</p>
                <h3>Connection Between Self-Portraits and Identity</h3>
                <span><i class="fa-regular fa-calendar"></i> May 15, 2020</span>
                <span><i class="fa-regular fa-eye"></i> 397 views</span>
              </div>
            </div>
          </div>
          <!-- right -->
          <div class="col-3" id="my_right_card">
            <div class="card border-0 rounded-0">
              <img src="../assets/images/artist-blog-01-480x356.jpg" alt="" class="card-img">
              <div class="card-body mb-2">
                <p>ARTIST</p>
                <h5>Pocket-Sized Notebooks Hold Miniature Painting</h5>
                <span><i class="fa-regular fa-calendar"></i> May 15, 2020</span>
                <span><i class="fa-regular fa-eye"></i> 603 views</span>
              </div>
            </div>
          </div>
          <!-- footer -->
          <div class="col-12 my-2" id="my_tips_footer">
            <p>Get in details now? <span>View all posts</span> <i class="fa-solid fa-arrow-right"></i></p>
          </div>
        </div>
      </div>
    </section>

    <!-- settima sezione: events & lets work together -->
    <section id="my_seventh_section" class="my-4 py-4">
      <div class="my_container_md">
        <div class="row debug">
          <div class="col-12 mb-4">
            <h1>Upcoming Events</h1>
            <h2>Let's Work Together</h2>
          </div>
          <div class="col-6 mb-4 d-flex debug">
            <div class="my_img">
              <img src="../assets/images/artist-event-04-250x300.jpg" alt="">
            </div>
            <div class="my_text">
              <ul>
                <li>
                  <p>NOV 22, 2020</p>
                </li>
                <li>
                  <h5>Storytelling Workshop</h5>
                </li>
                <li><span><i class="fa-solid fa-location-dot"></i> Texas, US</span></li>
              </ul>
            </div>
          </div>
          <div class="col-6 mb-4 d-flex debug">
            <div class="my_img">
              <img src="../assets/images/artist-event-03-250x300.jpg" alt="">
            </div>
            <div class="my_text">
              <ul>
                <li>
                  <p>OCT 10, 2020</p>
                </li>
                <li>
                  <h5>Painting Art Contest 2020</h5>
                </li>
                <li><span><i class="fa-solid fa-location-dot"></i> New York, US</span></li>
              </ul>
            </div>
          </div>
          <div class="col-6 mt-4 d-flex debug">
            <div class="my_text_right">
              <ul>
                <li>
                  <p>BOV 23, 2020</p>
                </li>
                <li>
                  <h5>International Art Fair</h5>
                </li>
                <li><span><i class="fa-solid fa-location-dot"></i> hamburg, Germany</span></li>
              </ul>
            </div>
            <div class="my_img">
              <img src="../assets/images/artist-event-02-250x300.jpg" alt="">
            </div>
          </div>
          <div class="col-6 mt-4 d-flex debug">
            <div class="my_text_right">
              <ul>
                <li>
                  <p>DEC 15, 2020</p>
                </li>
                <li>
                  <h5>Street Performance: Call for Artist</h5>
                </li>
                <li><span><i class="fa-solid fa-location-dot"></i> Illinois, US</span></li>
              </ul>
            </div>
            <div class="my_img">
              <img src="../assets/images/artist-event-02-250x300.jpg" alt="">
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ottava sezione: newsletter -->
    <section id="my_eighth_section" class="my-4 py-4">
      <div class="my_container_sm">
        <div class="row debug">
          <div class="col">
            <h3>Newsletter to get in touch</h3>
          </div>
          <div class="col-8" id="your_email">
            <span>Your e-mail </span><i class="fa-solid fa-arrow-right"></i>
          </div>
        </div>
      </div>
    </section>

  </div>
</template>

<style lang="scss" scoped>
@import '../assets/scss/colors.scss';
@import '../assets/scss/structure.scss';
@import '../assets/scss/font.scss';
@import '../assets/scss/variables.scss';

* {
  @include various;
  margin: 0 auto;
  /* text-align: center; */
  /* font-family: sans-serif; */
}

/* .debug {
  border: 1px dashed black;
} */

.btn {
  @include button;
}

#app_main {
  width: 100%;
}

.my_container_sm {
  @include mixin_container_sm;
}

.my_container_md {
  @include mixin_container_md;
}

.my_container_lg {
  @include mixin_container_lg;
}

.my_container_xl {
  @include mixin_container_xl;
}

.my_container_xxl {
  @include mixin_container_xxl;
}

#my_first_section {
  position: relative;
  width: 100%;
  background-color: $secondary;
  text-align: center;

  .row {
    height: 550px;
  }

  .my_col_sm {
    flex-basis: 30%;
    height: 60%;
  }

  .my_col_md {
    flex-basis: 40%;
  }
  #my_buttons{
    position: absolute;
    right: 0;
    top: 10%;
    background-color: white;
    padding: 1rem 0.5rem 0.5rem 0.5rem;
    border-radius: 5px;
    ul,li{
      margin-bottom: 1rem;
      list-style: none;
      i{
        font-size: 1.4rem;
        color: $regular;
      }
    }
  }
  #bg_clip_right{
    position: absolute;
    height: 100%;
    width: 100%;
    background-image: url('../src/assets/images/artist-shape-01-600x577.png'),
    url('src/assets/images/artist-shape-04-127x300.png')
    ;
    background-size: 50% 90%, auto;
    background-repeat: no-repeat;
    background-position-x: 85%, 85%;
    background-position-y: 10%, 20%;
  }
  #bg_clip_left{
    position: absolute;
    height: 100%;
    width: 100%;
    background-image: url('../src/assets/images/artist-hero-image-03-204x300.png'), url('../src/assets/images/artist-shape-03-201x300.png');
    background-size: auto, 15% auto;
    background-repeat: no-repeat;
    background-position-x: 30%, 10%;
    background-position-y: 75%, 20%;
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
      bottom: 80px;
      left: 100px;
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
  background-image: url('../src/assets/images/maxcoach-shape-03.png');
  background-size: 100% 75%;
  background-repeat: no-repeat;
  background-position: center;

  .row {
    height: 400px;
    opacity: 1;
  }
}

#my_third_section {
  position: relative;
  z-index: 1;
  text-align: center;

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

  .wave_bg {
    width: 100%;
    height: 200px;
    position: absolute;
    bottom: -5%;
    background-image: url('../src/assets/images/wave.svg');
    background-size: cover;
    background-size: 100% 300px;
    background-repeat: no-repeat;
    z-index: -1;
  }

  img {
    align-self: center;
  }
}

#my_forth_section {
  background-color: $secondary;
  position: relative;
  z-index: 1;
  @include testimonial;

  .row {
    height: 400px;
  }

  .inactive {
    opacity: 0.7;
  }
}

#my_fifth_section {
  @include courses;

  .row {
    /* height: 600px; */
  }

  .btn {
    text-align: center;
  }
}

#my_sixth_section {
  background-color: $tertiary;
  background-image: url('../src/assets/images/maxcoach-shape-03.png');
  background-size: 100% 75%;
  background-repeat: no-repeat;
  background-position: center;

  .row {
    height: 900px;
  }

  #my_left_card {
    @include tips;
    padding-top: 0rem;
  }
  #my_right_card{
    @include tips;
    padding-bottom: 7rem;
  }

  #my_center_card {
    background-color: transparent;
    border: none;
    height: 650px;
    display: flex;
    justify-content: end;

    /* bg image */
    background-image: url('../src/assets/images/artist-blog-02-500x680.jpg');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;

    #my_center_text {
      width: 400px;
      /* border: 1px dashed black; */
      padding: 1rem;
      padding-bottom: 2rem;
      align-self: baseline;
      color: white;

      p,
      h3,
      span {
        font-weight: 500;
        text-align: left;
        margin-bottom: 1rem;
        margin-right: 0.75rem;
      }
    }
  }
  #my_tips_footer{
    p{
      text-align: center;
      font-weight: 500;
    }
    span, i{
      color: $marked;
      text-decoration: underline;
    }
  }
}

#my_seventh_section {
  @include events;

  .col-6 {
    margin-top: 1rem;
    padding: 0;
  }
}

#my_eighth_section {
  background-color: $newsletter;
  @include newsletter;
  height: 200px;
  display: flex;
  align-items: center;
}
</style>