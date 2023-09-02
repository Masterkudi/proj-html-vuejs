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

    </div>
    <!-- QUINTA SEZIONE DEL MAIN -->
    <div>

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
    <div>

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

.container-subscribe {
  background-image: url(./assets/img/banner-2.jpg);
  background-position-y: center;
  background-position-x: center;
  padding: 6rem 15rem;
}</style>
