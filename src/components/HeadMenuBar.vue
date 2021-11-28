<template>
  <div id="menubar">
    <ul>
      <li>О сервере</li>
      <li>Правила</li>
      <li>Discord</li>
      <li>Рейтинг Hexed</li>
      <li>Глобальный рейтинг</li>
      <li>Написать тому кто это делал</li>
      <li>Хентай</li>
    </ul>
  </div>
</template>
<style>
#menubar {
  width: 95%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 0%;
  height: auto;
}

ul {
  text-transform: uppercase;
  text-align: left;
  display: inline;
  margin: 0;
  padding: 15px 4px 17px 0;
  list-style: none;
  -webkit-box-shadow: 0 0 5px rgba(0, 0, 0, 0.15);
  -moz-box-shadow: 0 0 5px rgba(0, 0, 0, 0.15);
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.15);
}
ul li {
  font: bold 12px/18px sans-serif;
  display: inline-block;
  margin-right: -5px;
  position: relative;
  padding: 15px 20px;
  background: #0000aa15;
  color: #00FF00;
  cursor: pointer;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -ms-transition: all 0.2s;
  -o-transition: all 0.2s;
  transition: all 0.2s;
}
ul li:hover {
  background: #00A000;
  color: #f7f7f7;
}
</style>