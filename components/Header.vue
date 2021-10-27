<template>
  <div class="header">
    <div class="header_icon">
      <span class="header_icon__line--top"></span>
      <span class="header_icon__line--middle"></span>
      <span class="header_icon__line--bottom"></span>
    </div>
    <div class="header_icon--text">Rese</div>
  </div>
</template>

<style scoped>
.header {
  display: flex;
}

.header_icon {
  display: inline-block;
  width: 36px;
  height: 32px;
  cursor: pointer;
  position: relative;
  left: 20px;
  top: 20px;
  background-color: blue;
  border-radius: 4px;
  padding: 2px;
}
.header_icon__line--top,
.header_icon__line--middle,
.header_icon__line--bottom {
  display: inline-block;
  width: 100%;
  height: 3px;
  background-color: white;
  position: absolute;

}
.header_icon__line--top {
  top: 20%;
  width: 40%;
}
.header_icon__line--middle {
  top: 50%;
  width: 80%;
}
.header_icon__line--bottom {
  top: 80%;
  width: 20%;
}
.header_icon--text {
  position: relative;
  left: 40px;
  top: 20px;
  color: blue;
  font-weight: bold;

}
</style>
