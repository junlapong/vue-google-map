<template>
  <div id="app">
    <google-map />
  </div>
</template>

<script>
import GoogleMap from "@/components/GoogleMap";

export default {
  name: "app",
  components: {
    GoogleMap
  },
  mounted() {
    console.log(">>> " + process.env.BASE_URL + " <<<");
  }
};

</script>
