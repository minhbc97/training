<template>
  <div>
    Hello
    <span>Message: {{ msg }}</span>

    <p>Using text interpolation: {{ rawHtml }}</p>
    <p>Using v-html directive: <span v-html="rawHtml"></span></p>
  </div>
</template>
<script>
export default {
  name: 'HomeView',
  data() {
    return {
      msg: 'Welcome to Your Vue.js + TypeScript App',
      rawHtml: '<span style="color: red">This should be red.</span>'
    }
  },
}
</script>
