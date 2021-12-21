<template>
  <div id="app">
    <Header/>

    <main>

      <GeneralJumbotron/>

      <Content/>

      <LinkExtra/>

      <PreFooter/>

    </main>

    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import GeneralJumbotron from "./components/GenerealJumbotron.vue";
import Content from "./components/Content.vue";
import LinkExtra from "./components/LinkExtra.vue";
import PreFooter from "./components/PreFooter.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    GeneralJumbotron,
    Content,
    LinkExtra,
    PreFooter,
    Footer,
  },
};
</script>

<style lang="scss">

body{

  font-family: 'Roboto', sans-serif;

}

*{

  margin: 0;
  padding: 0;
  box-sizing: border-box;

}

</style>
