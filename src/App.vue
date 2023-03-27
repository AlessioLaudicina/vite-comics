<script>
import TheHeader from "./components/TheHeader.vue"
import AppBlueMenu from "./components/AppBlueMenu.vue"
import TheFooter from "./components/TheFooter.vue"
import TheFooterBottom from "./components/TheFooterBottom.vue"

export default {
  components: {
    TheHeader,
    AppBlueMenu,
    TheFooter,
    TheFooterBottom,

  }

}

</script>

<template>
  <div class="container">

    <TheHeader></TheHeader>
    <main>
      <div class="main-up">
        Content goes here
      </div>


      <AppBlueMenu></AppBlueMenu>


    </main>
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

.container {
  margin: auto;
}

.main-up {
  height: 200px;
  background-color: black;
  color: white;
}
</style>
