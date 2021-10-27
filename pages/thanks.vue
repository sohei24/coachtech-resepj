<template>
  <div class="thanks__container">
    <Header />
    <div class="thanks__sub_container">
      <p class="thanks__text">会員登録ありがとうございます</p>
      <a href="/login" class="login_btn">ログインする</a>
    </div>
  </div>
</template>

<style scoped>
.thanks__container {
background-color: gainsboro;
width: 100vw;
height: 100vh;
}

.thanks__sub_container {
  width: 50%;
  margin: 100px auto 0;
  text-align: center;
  padding: 60px;
  box-shadow: 2px 2px 2px grey;
  background-color: white;
}

.thanks__text {
  font-size: 24px;
  margin-bottom: 40px;
}

.login_btn {
  text-decoration: none;
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 4px;
  margin-top: 30px;
}

</style>
