<template>
  <div id="app">
    <vue-form>
      <vue-input></vue-input>
    </vue-form>
  </div>
</template>

<script>

import VueForm from './components/forms/Form.vue';
import VueInput from './components/forms/inputs/FormInput.vue';

export default {
  name: 'App',
  components: {
    VueForm,
    VueInput,
  },
};
</script>

<style lang="scss">

</style>
