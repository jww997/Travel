<template>
  <div>
  	<home-header></home-header>
    <home-swiper></home-swiper>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
export default {
  name: 'HelloWorld',
  components: {
  	HomeHeader,
    HomeSwiper
  },
  data () {
    return {

    }
  }
}
</script>

<style lang="stylus" scoped>

</style>
