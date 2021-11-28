<template>
  <body>
    <div id="app">
      <HeadMenuBar />
      <img alt="Vue logo" src="./assets/logo.png" width="25%" />
      <HelloWorld msg="Hello Hentai-chan!" />
    </div>
  </body>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import HeadMenuBar from "./components/HeadMenuBar";

export default {
  name: "App",
  components: {
    HelloWorld,
    HeadMenuBar,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #AAFFAA;
  margin-top: 0px;
}
body {
  background-image: url("https://media.discordapp.net/attachments/810758723814948864/914600477453332600/back.png"); /*You will specify your image path here.*/
  -moz-background-size: cover;
  -webkit-background-size: cover;
  background-size: cover;
  background-position: top center !important;
  background-repeat: no-repeat !important;
  background-attachment: fixed;
}
</style>
