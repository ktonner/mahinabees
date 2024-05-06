<script setup lang="ts">
import AboutText from '../components/AboutText.vue';
</script>
<template>
  <main>
    <div class="about">
    <AboutText/>
    </div>
  </main>
</template>

<style>
.text p{
  margin-bottom:1em;
}
.scrollable {
   overflow-y: scroll;
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }


}
</style>