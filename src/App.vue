<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  name: 'MyComponent',
  components: {
    TheHeader,
    TheFooter
  }
}

</script>

<template>
  <TheHeader></TheHeader>
  <main>
    <!-- PRIMA SEZIONE DEL MAIN -->
    <div class="container-first text-center p-5">
      <div class="my-component">
        <h1>
          More About Damon Vaughn
        </h1>
        <p>Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author
          of
          the multi-million copy bestseller “The story of my life.”
        </p>
        <img src="./assets/img/hover-button2.png" alt="">
      </div>
    </div>
    <!-- SECONDA SEZIONE DEL MAIN -->
    <div class="container-sponsor text-center">
      <div>
        <a
          href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=2xUQZIwpxxyPRkpTADwA1wXYUkFyIvRJgVdfQI0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><img
            src="./assets/img/ebay-logotan-2x-400x132.png" alt=""></a>
        <a
          href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=2xUQZIwpxxyPRkpTADwA1wXYUkFyIvRJgVdfQI0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><img
            src="./assets/img/audible-logotan-2x-400x132.png" alt=""></a>
        <a
          href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=2xUQZIwpxxyPRkpTADwA1wXYUkFyIvRJgVdfQI0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><img
            src="./assets/img/bb-logotan-2x-400x132.png" alt=""></a>
        <a
          href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=2xUQZIwpxxyPRkpTADwA1wXYUkFyIvRJgVdfQI0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><img
            src="./assets/img/kindlefire-logotan-2x-400x132.png" alt=""></a>
      </div>
    </div>
    <!-- TERZA SEZIONE DEL MAIN -->
    <div class="container-audiobook">
      <div class="d-flex justify-content-center">
        <div class="d-flex">
          <div>
            <img src="./assets/img/audible-app-2x-400x418.png" alt="">
          </div>
          <div class="my-component audiobook text-center">
            <h2>New Audiobook</h2>
            <h3>NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h3>
            <p class="p text-secondary">Donec fringilla nunc eu turpis dignissim, at <br> euismod sapien tincidunt.
              Maecenas eleifend
              congue
              cursus.
            </p>
            <a class="rounded bg-success p-2 mt-4 text-decoration-none text-white" href="#"><i
                class="fa-brands fa-audible pe-3"></i>Buy This On Audible</a>
          </div>
        </div>
      </div>
    </div>
    <!-- QUARTA SEZIONE DEL MAIN -->
    <div class="container-testimonials">
      <div class="d-flex justify-content-between">
        <div>
          <h2>What The Critics Say</h2>
          <h3>TESTIMONIALS FROM AROUND THE WORLD</h3>
        </div>
        <div>
          <img src="./assets/img/hover-button3.png" alt="">
        </div>
      </div>
      <div class="d-flex justify-content-between">
        <div class="author">
          <h4>Best Author Of His <br> Generation</h4>
          <hr class="text-white">
          <h5 class="mb-4">This Book Will Change Your Perspective On Life</h5>
          <p class="mb-4 ">Donec fringilla sollicitudin molestie malesuada. Curabitur arcu erat, accumsan id imperdiet et,
            porttitor at
            sem. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Nulla quis lorem ut libero
            malesuada feugiat. Vestibulum ac diam sit amet.
            <br>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam voluptatum et recusandae ullam nihil. Aperiam
            aspernatur unde necessitatibus, nemo eius, animi pariatur nobis molestias porro magni accusantium.
            Reprehenderit, rerum aut?
          </p>
          <div class="d-flex flex-direction-row text-center">
            <img class="p-2" src="./assets/img/nytimes-logo-white-xsmall.png" alt="">
            <h5 class="p-2 mb-0">Justine Killpatrick</h5>
            <h5 class=" p-2 mb-0 text-success">The New York times</h5>
          </div>
        </div>
        <div>
          <div class="ps-6 pe-6">
            <div class="ps-4 pe-4 pb-4 text-center">
              <div style="background-color: #FEF7E9; padding: 3rem;">
                <h3>A True Masterpiece, Bravo!</h3>
                <p>Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed,
                  convallis
                  at tellus. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada
                  feug at.</p>
              </div>
              <div class="d-flex flex-direction-row" style="font-size: 1rem;">
                <img class="p-2" src="./assets/img/theguardian-xsmall.png" alt="">
                <h5 class="p-2 mb-0">Gerald Hendley</h5>
                <h5 class=" p-2 mb-0">The Guardian</h5>
              </div>
            </div>
            <div class="ps-4 pe-4 pt-4 text-center">
              <div style="background-color: #FEF7E9; padding: 3rem;">
                <h3>A Unique View On The World</h3>
                <p>Donec sollicitudin molestie malesuada. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem.
                  Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Nulla quis lorem ut libero
                  malesuada
                  feugiat. Vestibulum ac diam sit amet.</p>
              </div>
              <div class="d-flex flex-direction-row text-center">
                <img class="p-2" src="./assets/img/globe-xsmall.png" alt="">
                <h5 class="p-2 mb-0">Mary Maxey</h5>
                <h5 class=" p-2 mb-0">The Globe And Mail</h5>
              </div>
            </div>
          </div>
        </div>
      </div>


    </div>
    <!-- QUINTA SEZIONE DEL MAIN -->
    <div class="container-events">
      <div class="d-flex justify-content-center">
        <div class="align-items-center text-center">
          <h2 style="font-family: 'Playfair Display', serif;">Upcoming Events</h2>
          <h3>MEET THE AUTHOR IN PERSON</h3>
        </div>
      </div>
      <div class="row">
        <div class="cols-4 d-flex justify-content-between">
          <div class="p-3">
            <div class="bg-white">
              <img src="./assets/img/event-05-400x240.jpg" alt="">
              <div class="p-2">
                <h2 class="text-center align-items-center"><a class="text-center p-4 " href="#"
                    style="border-bottom: 1px solid black;">Chicago Book Signing</a></h2>
                <p class="p-4 text-center">
                  Mauris blandit aliquet elit, eget <br> tincidunt nibh pulvinar a. Mauris <br> blandit aliquet elit, eget
                  tincidunt nibh <br> pulvinar a nulla.
                </p>
              </div>

            </div>
          </div>
          <div class="p-3">
            <div class="bg-white">
              <img src="./assets/img/event-04-400x240.jpg" alt="">
              <div class="p-2">
                <h2 class="text-center align-items-center"><a class="text-center p-4 " href="#"
                    style="border-bottom: 1px solid black;">Meet & Greet With Amanda</a></h2>
                <p class="p-4 text-center">
                  Mauris blandit aliquet elit, eget <br> tincidunt nibh pulvinar a. Praesent <br> sapien massa, convallis
                  a pellentesque <br> nec, egestas.
                </p>
              </div>

            </div>
          </div>
          <div class="p-3">
            <div class="bg-white">
              <img src="./assets/img/event-07-400x240.jpg" alt="">
              <div class="p-2">
                <h2 class="text-center align-items-center"><a class="text-center p-4 " href="#"
                    style="border-bottom: 1px solid black;">Open Book: Dialogues</a></h2>
                <p class="p-4 text-center">
                  Mauris blandit aliquet elit, eget <br> tincidunt nibh pulvinar a. Mauris <br> blandit aliquet elit, eget
                  tincidunt nibh <br> pulvinar a nulla.
                </p>
              </div>


            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- SESTA SEZIONE DEL MAIN -->
    <div class="container-subscribe">
      <div class="d-flex justify-content-center">
        <div class="d-flex">
          <div>
            <div class="my-component subscribe text-center">
              <h2>Subscribe To My <br> Newsletter</h2>
              <h3>BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES</h3>
            </div>
            <nav class="navbar bg-body-transparent p-3">
              <div class="container-fluid">
                <form class="d-flex" role="search">
                  <input class="form-control p-2 me-3 " type="search" placeholder="Insert Your Email...*"
                    aria-label="Search">
                  <button class="btn bg-success text-white" type="submit">Subscribe</button>
                </form>
              </div>
            </nav>
            <p class="p text-center text-secondary">Donec fringilla nunc eu turpis dignissim, at euismod <br> sapien
              tincidunt.</p>
          </div>
        </div>
      </div>
    </div>
    <!-- SETTIMA SEZIONE DEL MAIN -->
    <div class="container-himself">
      <div class="d-flex p-4 justify-content-center">
        <div class="align-items-center text-center">
          <h2 style="font-family: 'Playfair Display', serif; color: #000; font-weight: 600;">Dig A Little Deeper Into
            Damon Vaughn</h2>
          <h3 class="text-success">FIND OUT MORE ABOUT THE AUTHOR HIMSELF</h3>
        </div>
      </div>
      <div class="row">
        <div class="cols-4 ps-5 pe-5 d-flex justify-content-center">
          <div class="p-4">
            <div class="image-one">
              <h2 class="p-2 text-center">About Me</h2>

            </div>
          </div>
          <div class="p-4">
            <div class="image-two">
              <h2 class="p-2 text-center">My Latest Book</h2>

            </div>
          </div>
          <div class="p-4">
            <div class="image-three">
              <h2 class="p-2 text-center">Book Signing</h2>

            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- OTTAVA SEZIONE DEL MAIN --> 
      <div class="container-articles">
        <div class="d-flex justify-content-between mb-3">
          <div>
            <h2 class="fs-1 mb-3" style="font-family: 'Playfair Display', serif; color: #000; font-weight: 600;">Recent
              Articles</h2>
            <h3 class="text-success fs-6 mb-3">READ THE LATEST ENTRIES</h3>
          </div>
          <div>
            <button class="btn text-white ps-5 pe-5 d-flex align-self-center" style="background-color: #F4B429;"
              type="submit">All
              Articles</button>
          </div>
        </div>
        <div class="d-flex justify-content-between">
          <div class="articles bg-white ps-5 pt-5 pe-5" style="width: 70%;">
            <img src="./assets/img/20-Tips-400x235.jpg" style="width: 100%;" alt="">
            <div class="p-4">
              <p class="fs-3">20 Creativity Tips</p>
              <p class="mb-4 fs-7">By admin|October 24th, 2019|Categories: Event, Tips & Tricks</p>
              <p class="mb-4 fs-5">Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae;
                Donec
                velit neque, auctor sit amet aliquam vel, ullamcorper sit amet.
              </p>
            </div>
          </div>
          <div class="ms-5" style="width: 40%; background-color: #fff;">
            <div class="articles text-center">
              <div style="background-color: #fff; padding: 2rem;">
                <img src="./assets/img/thumb-13-2x-700x441.jpg" alt="" style="width: 100%;">
                <div class="text-center p-3">
                  <div class="articles-text">
                    <h3>What's On Your Booklist?</h3>
                    <p>By admin|October 24th, 2019</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="articles text-center">
              <div style="background-color: #fff; padding: 2rem;">
                <img src="./assets/img/thumb-08-2x-700x441.jpg" alt="" style="width: 100%;">
                <div class="text-center p-3">
                  <div class="articles-text">
                    <h3>Instanbul Travel Guide</h3>
                    <p>By admin|October 24th, 2019</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
  </main>
  <TheFooter></TheFooter>
</template>

<style>
.container-first {
  justify-content: center;
}

.my-component h1 {
  font-family: 'Kristi', cursive;
  color: #F4B429;
  font-size: 3rem;
  margin-bottom: 2rem;
}

.my-component h2 {
  font-family: 'Playfair Display', serif;
  color: #fff;
  font-size: 3rem;
}

.my-component h3 {
  font-size: 1rem;
  color: #F4B429;
}

.my-component p {
  padding: 0rem 5rem;
  font-size: 2rem;
  margin-bottom: 3rem;
}

.my-component .p {
  font-size: 1.2rem;
  padding: 0;
  margin: 1rem 4rem;
}

.container-sponsor {
  background-color: #FEF7E9;
  padding: 2rem;
}

.container-sponsor img {
  width: 18%;
  padding: 2rem;
}

.my-component.audiobook {
  padding: 3rem;
  align-items: center;
}

.container-audiobook {
  background-image: url(./assets/img/banner.jpg);
  background-position-y: center;
  background-position-x: center;
  padding-top: 5rem;
  padding-left: 15rem;
  padding-right: 15rem;
}

.container-testimonials {
  padding: 4rem 10rem;
}

.container-testimonials h2 {
  font-family: 'Playfair Display', serif;
  font-size: 2.5rem;
  font-weight: 600;
}

.container-testimonials h3 {
  color: #49AA8B;
  font-size: 1.2rem;
  line-height: 2rem;
  font-weight: 500;
}

.author {
  background-image: url(./assets/img/testimonial2-2x.jpg);
  background-size: cover;
  color: #fff;
  padding: 5rem;
  border-radius: 0 0 70px 0;
  max-width: 45%;
  transition: transform 0.3s ease-in-out;
}

.author:hover {
  transform: scale(1.03);
}

.container-subscribe {
  background-image: url(./assets/img/banner-2.jpg);
  background-position-y: center;
  background-position-x: center;
  padding: 6rem 15rem;
}

.container-events {
  background-color: #FEF7E9;
  padding: 4rem 10rem;
}

.container-events h2 {
  font-size: 3rem;
  font-weight: 600;
}

.container-events a {
  font-size: 1.5rem;
  color: #000;
  text-decoration: none;
}

.container-events h3 {
  color: #F4B429;
  font-size: 1rem;
  margin-bottom: 2rem;
}

.container-himself {
  padding: 4rem 10rem;
}

.container-himself h2 {
  color: #fff;
  font-size: 2rem;
  font-weight: 400;
}

.container-himself h3 {
  font-size: 1rem;
}

.image-one {
  background-image: url(./assets/img/box-1.jpg);
  border-radius: 0 0 50px 0;
  background-size: cover;
  background-position-y: center;
  background-position-x: center;
  min-height: 400px;

}

.image-two {
  background-image: url(./assets/img/box-4.jpg);
  border-radius: 0 0 50px 0;
  background-size: cover;
  background-position-y: center;
  background-position-x: center;
  min-height: 100%;
}

.image-three {
  background-image: url(./assets/img/box-3.jpg);
  border-radius: 0 0 50px 0;
  background-size: cover;
  background-position-y: center;
  background-position-x: center;
  min-height: 100%;
}

.container-himself .row .p-4 {
  width: 30%;
  transition: transform 0.3s ease-in-out;
}

.container-himself .row .p-4:hover {
  transform: scale(1.03);
}

.container-articles {
  background-color: #FEF7E9;
  padding: 8rem 15rem;
}

/* PROVO AD AGGIUNGERE IL LINEAR GRADIENT ALLE 3 IMMAGINI DELL'8A SEZIONE MA APPARENTEMENTE NON FUNZIONA. */

/* .articles img {
  position: relative;
  overflow: hidden;
}

.articles img::before {
  content: ""; 
  position: absolute; 
  width: 100%;
  height: 0;
  bottom: 0;
  left: 0;
  background: linear-gradient(to top, rgba(255, 255, 255, 0), rgba(134, 253, 219, 1));
  transition: height 0.3s ease-in-out;
}

.articles img:hover::before {
  height: 100%;
}

.articles {
  position: relative;
}
 */
</style>
