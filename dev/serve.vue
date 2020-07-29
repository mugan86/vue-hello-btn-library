<script>
import Vue from 'vue';
import { HelloBtn } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    HelloBtn,
  }
});
</script>

<template>
  <div id="app">
    <HelloBtn />
  </div>
</template>
