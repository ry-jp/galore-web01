<template>
  <div class="flex justify-between ml-6 mr-6 mt-4">
    <nuxt-link to="/">
      <span class="emoji"> 🚲 </span>
    </nuxt-link>
    <button class="snipcart-checkout flex items-center">
      <Cart />
      <span
        class="snipcart-total-price ml-3 font-semibold text-sm text-pink"
      ></span>
    </button>
  </div>
</template>
<script>
import Cart from "./icons/cart.vue";
export default {
  components: {
    Cart,
  },
};
</script>
<style>
.emoji {
  font-size: 45px;
}
</style>