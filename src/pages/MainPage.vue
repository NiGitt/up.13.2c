<script setup>
import kakaData from "/src/data/kaka.json";
const kakas = kakaData;
</script>

<template>
  <div class="osnova">
    <div class="lenta">
      <p>ОБ ИГРЕ</p>
      <p>ОБЩЕНИЕ</p>
      <p>WIKI</p>
    </div>
    <div class="v-news">
      <div class="der">СОБЫТИЯ</div>
    <div class="news" v-for="(kaka, index ) in kakas" :key="index">
      <img :src="kaka.image" alt="#">
      <div class="try">
      <h2>{{kaka.title}}</h2>
      <p>{{kaka.description}}</p>
      </div>
    </div>
  </div>
  </div>
</template>

<style scoped>
  .osnova{
    background-color: black;
    width: 100%;
  }
  .lenta{
    display: flex;
    color: white;
    font-size: 16px;
    cursor: pointer;
    padding: 3em;
    width: 20%;
    margin-left:16%;

  }
.der{
  color: #A9AEB3;
  font-size: 2em;
}
 .v-news{
   display: flex;
   justify-content: space-evenly;
   flex-direction: column;
   width: 100%;
  }
 .news{
   display: flex;
   width: 60%;
   padding: 1em;
 }
  .news img {
    height: 30%;
    width: 30%;
  }
.try{
  width: 100%;
  color: #A9AEB3;
  padding-left: 1em;
  font-size: 1em;

}
.try h2{
  color: #C61919;
}
</style>