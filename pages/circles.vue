<template>
  <section>
    <div class="header">
      <div class="logo">MIKESPIN</div>
      <nav>
        <ul>
          <li>Home</li>
          <li>Next</li>
          <li>Prev</li>
        </ul>
      </nav>
    </div>
    <div class="circle-container">
      <div class="vertical-line"></div>
      <div class="horizontal-line"></div>
    </div>
  </section>
</template>

<script lang="ts">
// https://www.appart.agency/
// https://www.youtube.com/watch?v=oYZT2VBATIo&ab_channel=ConorBailey
import Vue from 'vue'

export default Vue.extend({
  name: 'CirclesPage',
})
</script>
