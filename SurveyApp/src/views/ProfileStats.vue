<template>
  <div class="">
    <AppWorkInProgress />
  </div>
</template>

<script>
import AppWorkInProgress from '../components/AppWorkInProgress.vue';
// import { useMainStore } from '../stores/main';

export default {
  data() {
    return {
      // mainStore: useMainStore()
    }
  },
  components: {
    AppWorkInProgress
  }
};
</script>