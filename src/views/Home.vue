<template>
  <div class="home">
      <header class="header">
            
      </header>
      <main class="main">
        <div class="banner">
            <div class="swiper-container">
                <div class="swiper-wrapper">
                    <div class="swiper-slide">1</div>
                    <div class="swiper-slide">2</div>
                    <div class="swiper-slide">3</div>
                </div>

            </div>
        </div>
      </main>
      <Footer></Footer>
  </div>
</template>

<script>
import Footer from '../components/Footer.vue';
export default {
e:"home",
data() {
    return {
        list:[
            {title:"承担奖励"}
        ]
    }
},
components:{
    Footer
}
}
</script>

<style>

</style>
