<template>
  <div id="app">
    <font-awesome-icon :icon="['fas', 'bars']" />
    asd
  </div>
</template>

<script>
import { library } from '@fortawesome/fontawesome-svg-core';
import { faBars } from '@fortawesome/free-solid-svg-icons';

library.add(faBars);

export default {
  name: 'App',
  components: {},
};
</script>

<style lang="scss">
#app {
}
</style>
