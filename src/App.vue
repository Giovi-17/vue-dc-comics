<template>
  <div id="app">
    <Header/>

    <main>

      <Content/>
      
      <LinkExtra/>

    </main>

    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import LinkExtra from "./components/LinkExtra.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Content,
    LinkExtra,
    Footer
  },
};
</script>

<style lang="scss">

*{

  margin: 0;
  padding: 0;
  box-sizing: border-box;

}

</style>
