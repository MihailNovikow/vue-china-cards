<template>
  <div class="page">
    <nav>
      <ul class="nav"><img class="header-logo-img" src="../assets/logo.png">
        <li><a href="#">Тренажеры</a></li>
        <li><a href="#">О Китае</a></li>
        <li><a href="#">Личный кабинет</a></li>
      </ul>
    </nav>
   </div>
</template>
<script>
export default {
  name: 'HeaderComp',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
* {
  background: #AFB9FF;
}
.page {
    display: flex;
    align-items: center;
    background: #AFB9FF;
    justify-content: center;
}
.header-logo-img {
    margin-right: 190px;
    width: 129px;
    height: 50px;
    left: 485px;
    top: 38px;
}
.nav {
    margin-top: 37px;
    margin-bottom: 90px;
    /* margin-left: 160px; */
    /* margin-right: 160px; */
    /* width: 950px; */
    display: flex;
    list-style-type: none;
    /* padding-left: 10px; */
    background: #AFB9FF;
    height: 120px;
    left: 0px;
    /* top: 200px; */
    /* width: 1440px; */
    align-items: center;
    justify-content: center;
}
.nav>li {
  display: flex;
  margin-left: 50px;
  margin-right: 50px;
}

.nav>li>a {
  font-family: 'Montserrat Alternates';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */

  text-decoration: none;
  color: #FFFFFF;
}

a:hover {
  opacity: 0.8;
  background: #5f994d;
}
</style>
