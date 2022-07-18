<template>
  <div id="app">
    <DcHeader/>
    <DcCards/>
    <DcProducts/>
    <DcFooter/>
  </div>
</template>

<script>
import DcHeader from './components/DcHeader.vue'
import DcCards from './components/DcCards.vue'
import DcProducts from './components/DcProducts.vue'
import DcFooter from './components/DcFooter.vue'

export default {
  name: 'App',
  components: {
    DcHeader,
    DcCards,
    DcProducts,
    DcFooter,
  }
}
</script>


<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import './style/variables.scss';
@import './style/common.scss';
</style>

