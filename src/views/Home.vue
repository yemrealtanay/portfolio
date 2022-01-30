<template>
  <div class="customWrapper">
    <div class="big1">
      <p>hello</p>
    </div>
    <div class="big2">
      <p>thisis</p>
    </div>
    <div class="bigName">
      <p>YunusEmre</p>
    </div>
    <div class="bigLastName">
      <p>ALTANAY</p>
    </div>
    <div class="customMenuWrapper">
        <span class="bigLink1 pa-8" href="">designer</span>
        <span class="separator pa-8" href="">k</span>
        <span class="bigLink2 pa-8" href="">developer</span>
    </div>
  </div>
</template>

<style>
.customMenuWrapper {
  width: 100%;
  text-align: center;
  position: absolute;
  bottom: 50px;
}
.customWrapper {
  height: 100%;
  width: 100%;
  position: absolute;
}
.bigLink1 {
  font-size: 35px;
  font-family: "ink free", sans-serif;
}
.separator {
  font-size: 35px;
  font-family: "Marlett", sans-serif;
}
.bigLink2 {
  font-size: 35px;
  font-family: "TerminessTTF Nerd Font", sans-serif;
}
.big1 {
  font-size: 250px;
  font-family: "Gotham Black", sans-serif;
  position: relative;
  top: -100px;
  right: 35px;
  transition: 0.5s;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
}
.big2 {
  font-size: 200px;
  font-family: "Gotham Black", sans-serif;
  position: relative;
  top: -280px;
  left: 135px;
  transition: 0.5s;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
}
.bigName {
  font-size: 250px;
  font-family: "Gotham Black", sans-serif;
  position: relative;
  top: -510px;
  right: 55px;
  transition: 0.5s;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
}
.bigLastName {
  font-size: 400px;
  font-family: "Gotham Black", sans-serif;
  position: relative;
  top: -780px;
  transition: 0.5s;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
}
.bigLastName:hover {
  font-size: 405px;
  transition: 0.3s;
  mouse-cursor: default;
}
.bigName:hover {
  font-size: 255px;
  transition: 0.3s;
  mouse-cursor: default;
}
.big2:hover {
  font-size: 205px;
  transition: 0.3s;
  mouse-cursor: default;
}
.big1:hover {
  font-size: 255px;
  top: -105px;
  transition: 0.3s;
  mouse-cursor: default;
}
</style>

<script>

export default {
  name: "Home",
};
</script>
