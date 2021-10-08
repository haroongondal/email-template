<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <button @click="change">change template</button>
    reload for welcome template

    <Email v-if="emailType === 'recieved'" />
    <EmailDelivered v-if="emailType === 'delivered'" />
    <EmailWelcome v-if="emailType === 'welcome'" />
  </div>
</template>

<script>
import Email from "./components/Email.vue";
import EmailDelivered from "./components/EmailDelivered.vue";
import EmailWelcome from "./components/EmailWelcome.vue";

export default {
  name: "App",
  data() {
    return {
      emailType: "welcome"
    };
  },
  components: {
    Email,
    EmailDelivered,
    EmailWelcome
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
