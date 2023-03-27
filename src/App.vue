<script>
import TheHeader from "./components/TheHeader.vue"
import TheFooter from "./components/TheFooter.vue"

export default {
  components: {
    TheHeader,
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

    <div class="main-bottom">

    </div>
  </main>
  <TheFooter></TheFooter>
</template>

<style>
.main-up {
  height: 200px;
  background-color: black;
  color: white;
}
</style>
