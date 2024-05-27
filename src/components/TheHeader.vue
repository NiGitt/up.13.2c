<script setup>

</script>

<template>
    <div class="header">
      <div class="warface">
        <img src="../assets/images/warface.png" alt="#">
        <h1>WARFACE</h1>
      </div>
        <div class="p">
          <p>Войти</p>
          <p>Регистрация</p>
        </div>
    </div>
</template>

<style scoped>
.warface{
  display: flex;
  align-self: center;
  flex-direction: column;
  cursor: pointer;
}


.header{
  background-image: url("../assets/images/warface (2).png" );
  display: flex;
  margin: 0 auto;
  justify-content: space-around;
  width: 100%;
  background-size:100% 100%;
  background-repeat: no-repeat;
  padding: 1.5em;
}
.header h1{
  color: white;
  font-size: 16px;
  padding: 1.5em;
}
.p{
  display: flex;
  color: white;
  font-size: 16px;
  height: 20px;
  padding: 1em;
  cursor: pointer;
}
p:last-child{
  margin-left: 3em;
}
</style>