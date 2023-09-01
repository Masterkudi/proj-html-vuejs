<script>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';

export default {
  components: {
    TheHeader,
    TheFooter
  }
}

</script>

<template>
  <TheHeader></TheHeader>
  <main>
    <div class="container bg-white">
      <h1 class="my-component">
        More About Damon Vaughn
      </h1>
      <p>Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author of
      the multi-million copy bestseller “The story of my life.”</p>
    </div>
  </main>
  <TheFooter></TheFooter>
</template>

<style></style>
