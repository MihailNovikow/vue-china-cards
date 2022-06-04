<template>
  <div id="app">
    <HeaderComp></HeaderComp>
    <div class="page">
<div class="bg-white">
			<h1 class="title">Таблица ключей китайских иероглифов</h1>
			<div class="grid">
      <CardComp
      v-for="(card, index) in cards" 
      :key="card.id"
      :title="card.title"
      :index="index"
      ></CardComp>
    </div></div></div>
  </div>
</template>

<script>
import CardComp from './components/CardComp.vue';

import HeaderComp from './components/HeaderComp.vue';
export default {
  name: 'App',
  components: {
    CardComp,
    HeaderComp,
     },
  data() {
    return {
       newCardText: '111',
cards: [
  {       id: 1,
          title: ''
        },
        {
          id: 2,
          title: ''
        },
        {
          id: 3,
          title: ''
        },
        {
          id: 4,
          title: ''
        },{
          id: 5,
          title: ''
        },{
          id: 6,
          title: ''
        },{
          id: 7,
          title: ''
        },{
          id: 8,
          title: ''
        },{
          id: 9,
          title: ''
        },{
          id: 10,
          title: ''
        },{
          id: 11,
          title: ''
        },{
          id: 12,
          title: ''
        },{
          id: 13,
          title: ''
        },{
          id: 14,
          title: ''
        },{
          id: 15,
          title: ''
        },{
          id: 16,
          title: ''
        },{
          id: 17,
          title: ''
        },{
          id: 18,
          title: ''
        },{
          id: 19,
          title: ''
        },{
          id: 20,
          title: ''
        },{
          id: 21,
          title: ''
        },{
          id: 22,
          title: ''
        },{
          id: 23,
          title: ''
        },{
          id: 24,
          title: ''
        },{
          id: 25,
          title: ''
        },{
          id: 26,
          title: ''
        },{
          id: 27,
          title: ''
        },{
          id: 28,
          title: ''
        },{
          id: 29,
          title: ''
        },{
          id: 30,
          title: ''
        },{
          id: 31,
          title: ''
        },{
          id: 32,
          title: ''
        },{
          id: 33,
          title: ''
        },{
          id: 34,
          title: ''
        },{
          id: 35,
          title: ''
        },{
          id: 36,
          title: ''
        },{
          id: 37,
          title: ''
        },{
          id: 38,
          title: ''
        },{
          id: 39,
          title: ''
        },{
          id: 40,
          title: ''
        },{
          id: 41,
          title: ''
        },{
          id: 42,
          title: ''
        },{
          id: 43,
          title: ''
        },{
          id: 44,
          title: ''
        },{
          id: 45,
          title: ''
        },{
          id: 46,
          title: ''
        },{
          id: 47,
          title: ''
        },{
          id: 48,
          title: ''
        },{
          id: 49,
          title: ''
        },{
          id: 50,
          title: ''
        },
        {
          id: 51,
          title: ''
        },
        {
          id: 52,
          title: ''
        },
        {
          id: 53,
          title: ''
        },
        {
          id: 54,
          title: ''
        },{
          id: 55,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },{
          id: 51,
          title: ''
        },
        
]
    }
} 
}
</script>

<style>
* {
  box-sizing: border-box;
}
.page>* {
background: #AFB9FF;
}
.bg-white {
    display: flex;
    /* width: 950px; */
    height: 3651px;
    left: 485px;
    top: 177px;
    background: #F9F9F9;
    border-radius: 21px;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.grid {
    padding-left: 50px;
    padding-right: 55px;
    display: grid;
    grid-template-columns: repeat(8, 1fr);
    grid-template-rows: repeat(27, 1fr);
    margin-top: 250px;
    grid-column-gap: 20px;
    grid-row-gap: 20px;
    /* width: 950px; */
    height: 3500px;
    /* left: 485px; */
    /* top: 177px; */
    margin-top: 45px;
    background: transparent;
    /* border-radius: 21px; */
    justify-items: center;
    align-items: center;
}
.title {
    margin-left: 57px;
    margin-top: 78px;
    display: flex;
    font-family: 'Montserrat Alternates';
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 29px;
    background: #F9F9F9;
    color: #373C65;
    justify-content: flex-start;
}
@import url('https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@500;600&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@500;600&family=Roboto&display=swap');
</style>
