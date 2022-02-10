<template>
  <div id="app">
    <DynamicComponent/>
  </div>
</template>

<script>
import DynamicComponent from './components/DynamicComponent.vue'

export default {
  name: 'App',
  components: {
    DynamicComponent
  }
}
</script>
