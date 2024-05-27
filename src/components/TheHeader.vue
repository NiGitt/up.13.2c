<script setup>

</script>

<template>
    <div class="header">
      <div class="warface">
        <img src="../assets/images/warface.png" alt="#">
        <p>WARFACE</p>
      </div>
      <div class="button_head">
      <button >Войти</button>
      <button >Регистрация</button>
    </div>
    </div>
</template>

<style scoped>
.warface{
  padding-top: 2em;
  padding-bottom: 2em;
}
.header{
  background-image: url("../assets/images/1.jpg" ) ;
  display: flex;
  margin: 0 auto;
  justify-content: space-around;
  width: 100%;
  background-size:100% 250%;
  background-repeat: no-repeat;
}
.header p{
  color: white;
}
.button_head{
  height: 20px;
  color: white;
  background-color: rgba(255, 255, 255, 0);
  border: none;
  outline: none;
  cursor: pointer;
  display: flex;
  align-items: end;

}
</style>