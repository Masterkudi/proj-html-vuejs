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
        <img src="./assets/img/ebay-logotan-2x-400x132.png" alt="">
        <img src="./assets/img/audible-logotan-2x-400x132.png" alt="">
        <img src="./assets/img/bb-logotan-2x-400x132.png" alt="">
        <img src="./assets/img/kindlefire-logotan-2x-400x132.png" alt="">
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
            <h2 style="font-family: 'Playfair Display', serif;">Dig A Little Deeper Into Damon Vaughn</h2>
            <h3 class="text-success">FIND OUT MORE ABOUT THE AUTHOR HIMSELF</h3>
          </div>
        </div>
        <div class="row">
          <div class="cols-4 ps-5 pe-5 d-flex justify-content-center">
            <div class="p-4">
              <div class="image-one">

              </div>
            </div>
            <div class="p-4">
              <div class="image-two">

              </div>
            </div>
            <div class="p-4">
              <div class="image-three">

              </div>
            </div>
          </div>
        </div>
      </div>
    <!-- OTTAVA SEZIONE DEL MAIN -->
    <div>

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
  font-size: 2.5rem;
  font-weight: 600;
}
.container-himself h3 {
  font-size: 1rem;
}

.container-himself .row .p-4 {
  width: 100%;
  border-radius: 0 0 50px 0;
  transition: transform 0.3s ease-in-out;
}
.container-himself .row .p-4:hover {
  transform: scale(1.03);
}
.image-one {
  background-image: url(./assets/img/box-1.jpg);
}
.image-two {
  background-image: url(./assets/img/box-4.jpg);
}
.image-three {
  background-image: url(./assets/img/box-3.jpg);
}
</style>
