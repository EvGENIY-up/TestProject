<script setup>
import Position from './components/Position.vue'
import Headers from "./components/Headers.vue";
import Sidebar from "./components/Sidebar.vue";
</script>

<template>
  <div class="wrapper">
    <headers/>
    <main>
      <sidebar/>
      <h1 class="title-name">Название категории</h1>
      <div class="positions">
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
        <position/>
      </div>
    </main>
    </div>
</template>

<style scoped lang="scss">
main {
  @media (min-width: 1440px) {
    display: flex;
    justify-content: space-around;
  }
}
.title-name{
  margin-left: 24px;
  font-weight: 400;
  font-size: 22px;

  @media (min-width: 1440px) {
    display: none;
  }
}
.positions{
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;

  @media (min-width: 1440px) {
    max-width: 924px;
    margin-top: 18px;
    justify-content: space-between;
  }
  @media (min-width: 1920px) {
    max-width: 1404px;
  }
}
</style>
