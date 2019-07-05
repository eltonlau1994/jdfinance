<template lang="html">
    <div class="home">
        <Header></Header>
        <homeSlider></homeSlider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
        <Product></Product>
        <Life></Life>
        <Footer></Footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Header from '@/components/header.vue'
import Footer from '@/components/footer.vue'
import Navbar from '@/components/navbar.vue'
import homeSlider from '@/components/home/homeSlider.vue'
import Novice from '@/components/home/novice.vue'
import Borrow from '@/components/home/borrow.vue'
import Money from '@/components/home/money.vue'
import Product from '@/components/home/product.vue'
import Life from '@/components/home/life.vue'
export default {
  app: 'home',
  components: {
    Header,
    homeSlider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    Footer,
    Navbar
  }
}
</script>