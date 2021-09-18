<!-- Please remove this file from your project -->
<template>
  <div class="grid-container">
    <span class="name-box">
      Ea Bla Yoga
    </span>
    <div class="menu-box">
      <div class="menu-items">
        <v-btn>Menu 1</v-btn>
        <v-btn>Menu 2</v-btn>
        <v-btn>Menu 3</v-btn>
        <v-btn>Menu 4</v-btn>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Architects+Daughter&display=swap");
.grid-container {
  color: white;
  display: grid;
  grid-template-columns: 33.3vw 33.3vw 33.3vw;
  grid-template-rows: 16.6vh 16.6vh 16.6vh 16.6vh 16.6vh 16.6vh;
}
.name-box {
  grid-column: 2 / 3;
  grid-row: 5 / 7;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Architects Daughter", cursive;
  font-size: 50px;
}
.menu-box {
  grid-column: 2 / 4;
  grid-row: 1 / 2;
  display: grid;
  grid-template-columns: 50% 50%;
  grid-template-rows: 50% 50%;
  font-family: "Architects Daughter", cursive;
  font-size: 25px;
}
.menu-items {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
</style>
