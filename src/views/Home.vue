<template>
  <div>
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
    <div class="bigLink1">
      <p href="">designer</p>
    </div>
    <div class="separator">
      <p href="">k</p>
    </div>
    <div class="bigLink2">
      <p href="">developer</p>
    </div>
  </div>
</template>

<style>
.bigLink1 {
  font-size: 35px;
  font-family: "ink free", sans-serif;
  position: relative;
  color: #222222;
  top: -900px;
  left: 600px;
  width: 300px;
  float: left;
}
.separator {
  font-size: 35px;
  font-family: "Marlett", sans-serif;
  position: relative;
  color: #222222;
  top: -900px;
  left: 600px;
  width: 250px;
  float: left;
}
.bigLink2 {
  font-size: 35px;
  font-family: "TerminessTTF Nerd Font", sans-serif;
  position: relative;
  color: #222222;
  top: -900px;
  left: 600px;
  margin-left: 320px;
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
