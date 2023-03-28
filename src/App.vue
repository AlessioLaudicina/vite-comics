<script>
import TheHeader from "./components/TheHeader.vue"
import AppMain from './components/AppMain.vue';
import AppBlueMenu from "./components/AppBlueMenu.vue"
import TheFooter from "./components/TheFooter.vue"
import TheFooterBottom from "./components/TheFooterBottom.vue"

export default {
  components: {
    TheHeader,
    AppMain,
    AppBlueMenu,
    TheFooter,
    TheFooterBottom,

  }

}

</script>

<template>
  <div class="container">

    <TheHeader></TheHeader>

    <AppMain></AppMain>


    <AppBlueMenu></AppBlueMenu>



    <TheFooter></TheFooter>
    <TheFooterBottom></TheFooterBottom>


  </div>
</template>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  font-family: 'PT Sans Narrow', sans-serif;
}

.container {
  margin: auto;
}
</style>
