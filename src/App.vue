<template>
<my-header/>
  <router-view/>
  <my-footer/>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyFooter from './components/MyFooter.vue';

export default {
  components: {
    MyHeader,
    MyFooter
  }
}
</script>
<style lang="scss">

</style>
