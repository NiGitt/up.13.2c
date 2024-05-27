<script setup>

</script>

<template>
    <div class="footer">
      <div class="img">
        <img src="../assets/images/warface.png" alt="#">
      </div>
      <div class="obigre">
        <h4>ОБ ИГРЕ</h4>
        <p>Торговая площадка</p>
        <p>Системные требования</p>
      </div>
      <div class="obsh">
        <h4>Общение</h4>
        <p>Социальные сети</p>
      </div>
      <div class="wiki">
        <h4>WIKI</h4>
        <p>Помощь</p>
        <p>Документы</p>
      </div>
    </div>
</template>

<style scoped>
.footer {
  display: flex;
  background-color: #191921;
  align-items: start;
  justify-content: space-evenly;
  width: 100%;
  margin-top: 50em;

}
.footer p{
  color: #6C6C77;
  cursor: pointer;
}
.footer h4{
  color: #6C6C77;
  cursor: pointer;
}
.img{
  display: flex;
  align-self: center;
}
</style>