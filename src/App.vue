
<template>
  <div class="container">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

.container{
  background-image: linear-gradient(navy 20%, salmon 80%);
  width: 100vw;
  height: 100vh;
  color: white;
  text-align: center;
}

.padding-left{
  padding-left: 50px;
}

.radius{
  border-radius: 0px 0px 50px 0px;
  border-bottom: 5px solid black;
}

</style>
