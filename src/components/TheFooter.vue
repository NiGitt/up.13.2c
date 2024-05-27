<script setup>

</script>

<template>
    <div class="footer">
      <div class="foot">
      <div class="tru_img">
        <img src="../assets/images/warface.png" alt="#">
        <p>WARFACE</p>
      </div>
      <div class="obigre">
        <h4>ОБ ИГРЕ</h4>
        <router-link to="/aboutplay"><p>Системные требования</p></router-link>
      </div>
      <div class="obsh">
        <h4>ОБЩЕНИЕ</h4>
        <p>Социальные сети</p>
      </div>
      <div class="wiki">
        <h4>WIKI</h4>
        <p>Помощь</p>
      </div>
        <div class="cry_img">
          <img src="../assets/images/cry.png" alt="#">
          <img src="../assets/images/vkplay1.png" alt="#">
          <img src="../assets/images/astrum.png" alt="#">
          <img src="../assets/images/ico12.png" alt="">
        </div>
      </div>
    </div>
</template>

<style scoped>
.footer {
width: 100%;
}
.foot{
  display: flex;
  background-color: #191921;
  align-items: start;
  justify-content: space-evenly;
  width: 100%;
  padding: 2em;
}
.footer p{
  color: #6C6C77;
  cursor: pointer;
  margin-bottom: 0.5em;
  font-size: 1.5em;
}
.footer h4{
  color: #6C6C77;
  cursor: pointer;
  margin-bottom: 1em;
  font-size: 1.5em;
}
.cry_img{
  display: flex;
  flex-direction: column;
}
.cry_img img:last-child{
  padding-left: 5em;
}
.tru_img{
  display: flex;
  flex-direction: column;
  padding-top: 2em;

}
.tru_img p{
  color: white;
  padding: 1em;
}
</style>