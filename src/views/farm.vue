<template>
  <div>
    <AppNavbar />
    <Main />
    <Blog />
  </div>
</template>
<script>
import AppNavbar from "../components/farm/AppNavbar.vue";
import Main from "../components/farm/Main.vue";
import Blog from "../components/home/Blog.vue";
export default {
  components: {
    AppNavbar,
    // Header,
    Main,
    Blog,
    // NewF
  },
};
</script>
