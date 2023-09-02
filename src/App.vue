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
    <div class="container-first text-center p-5 m-5">
      <div class="my-component">
        <h1>
          More About Damon Vaughn
        </h1>
        <p>Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author
          of
          the multi-million copy bestseller “The story of my life.”
        </p>
        <button class="bg-success rounded border-0 p-2 text-white">Meet The Author</button>
      </div>
    </div>
    <div class="container-sponsor">
      <div>
        
      </div>
    </div>
  </main>
  <TheFooter></TheFooter>
</template>

<style>
.container-first {
  justify-content: center;
}
.my-component {
  padding: 2rem;
}

.my-component h1 {
  font-family: 'Kristi', cursive;
  color: #F4B429;
  font-size: 4rem;
}
.my-component p {
  font-size: 2rem;
}
</style>
