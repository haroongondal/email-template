<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <button @click="change">email</button>
    <Email v-if="emailType === 'recieved'" />
    <EmailDelivered v-else />
  </div>
</template>

<script>
import Email from "./components/Email.vue";
import EmailDelivered from "./components/EmailDelivered.vue";

export default {
  name: "App",
  data() {
    return {
      emailType: "recieved"
    };
  },
  components: {
    Email,
    EmailDelivered
  },
  methods: {
    change() {
      this.emailType === "recieved"
        ? (this.emailType = "delivered")
        : (this.emailType = "recieved");
    }
  }
};
</script>

<style lang="scss" scoped></style>
