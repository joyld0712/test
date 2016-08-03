<template>
  <div id="app">
	<heards></heards>
	<bodys></bodys>
	<footers></footers>
  </div>
</template>

<script>
import heards from './components/heard.vue'
import bodys from './components/body.vue'
import footers from './components/footer.vue'
export default {
   components: {
    heards,footers,bodys
  },
  data () {
    return {
      msg: 'Hello Vue!'
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
