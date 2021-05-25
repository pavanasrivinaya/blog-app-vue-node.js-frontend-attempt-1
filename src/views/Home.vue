<template>
  <div class="home">
    <Header />
    <Posts />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "../components/Header";
import Footer from "../components/Footer";
import Posts from "../components/Posts";

export default {
  name: "Home",
  components: {
    Header,
    Footer,
    Posts,
  },
};
</script>
