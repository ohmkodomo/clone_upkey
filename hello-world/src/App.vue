<template>
  <div>
    <Header />
    <router-view />
  </div>
</template>

<script>
// import Content from "./components/Content"
import Header from "./components/Header";

export default {
  name: "App",
  components: {
    // Content,
    Header,
  },

  data: () => ({
    //
  }),
};
</script>


