<template>
  <div id="app">
    <credit-card-form />
  </div>
</template>

<script>
import CreditCardForm from "./components/CreditCardForm.vue";
export default {
  components: {
    CreditCardForm,
  },
};
</script>

<style lang="scss">
#app {
  @import url("https://fonts.googleapis.com/css?family=Source+Code+Pro:400,700&display=swap");
  @import url("https://fonts.googleapis.com/css?family=Roboto&display=swap");
  font-family: "Roboto", sans-serif;
  margin: 5rem auto 0;
  text-align: center;
  color: #2c3e50;
  padding: 0;

  * {
    box-sizing: border-box;
    &:focus {
      outline: none;
    }
  }
}
</style>
