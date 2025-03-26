<template>
  <AutoDiagnostics />
</template>

<script>
import AutoDiagnostics from './components/AutoDiagnostics.vue';

export default {
  components: {
    AutoDiagnostics
  }
};
</script>
<style>
html, body {
  background: url('src/assets/background.jpg') no-repeat center center fixed;
  background-size: cover;
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
</style>