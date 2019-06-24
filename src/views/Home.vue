<template lang="html">
    <div class="home">
        <Header></Header>
        <homeSlider></homeSlider>
    </div>
</template>

<script>
import Header from '@/components/header.vue'
import homeSlider from '@/components/home/homeSlider.vue'
export default {
  app: 'home',
  components: {
    Header,
    homeSlider
  }
}
</script>