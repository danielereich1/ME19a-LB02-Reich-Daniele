<template>
  <div>
    <MyComponent />
  </div>
</template>

<script>
/* Import all components */
import Demos from './components/VueDirectives'

export default {
  components: {
    MyComponent: Demos
  },
}
</script>

<style lang="scss">
//Import of global-style
@import 'styles/global';
</style>
