<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './Components/Header.vue'

export default {
  name: 'App',
  components: {
      Header,
  }
}
</script>

<style>
  :root {
    --header-height: 5rem;

    --dark-10: #151B26;
    --dark-20: #09090B;
    --dark-30: #151B26;
    --dark-40: #A3A3A3;

    --support-01: #2962FF;
    --support-02: #0BB07B;
    --support-03: #FFCE52;
    --support-04: #F03D3D;
    --support-05: #E0E0E0;


    --brand-color-blue-gradient-01: #00A3FF;
    --brand-color-blue-gradient-02: #0054C6; 
  }
</style>
