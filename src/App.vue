<template>
  <div id="app">
    <DcHeader/>
    <DcMain/>
    <DcProducts/>
    <DcFooter/>
  </div>
</template>

<script>
import DcHeader from './components/DcHeader.vue'
import DcMain from './components/DcMain.vue'
import DcProducts from './components/DcProducts.vue'
import DcFooter from './components/DcFooter.vue'

export default {
  name: 'App',
  components: {
    DcHeader,
    DcMain,
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

