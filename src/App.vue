<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import { components } from 'aws-amplify-vue'
export default {
  components: {
    ...components
  }
}
</script>
