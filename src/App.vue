<template>
  <h1>{{ msg }}</h1>
  <SayHello />
</template>

<script>
import SayHello from "~/components/SayHello";

export default {
  data() {
    return {
      msg: "hello webpack!"
    };
  },
  components: {
    SayHello
  }
};
</script>
