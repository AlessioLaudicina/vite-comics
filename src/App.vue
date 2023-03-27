<script>
import TheHeader from "./components/TheHeader.vue"
import TheFooter from "./components/TheFooter.vue"
import AppBlueMenu from "./components/AppBlueMenu.vue"

export default {
  components: {
    TheHeader,
    AppBlueMenu,
    TheFooter

  }

}

</script>

<template>
  <TheHeader></TheHeader>
  <main>
    <div class="main-up">
      Content goes here
    </div>


    <AppBlueMenu></AppBlueMenu>


  </main>
  <TheFooter></TheFooter>
</template>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main-up {
  height: 200px;
  background-color: black;
  color: white;
}
</style>
