<template>
  <button class="button" :innerText="msg" v-on:click="handleClick">
  </button>
</template>

<script>
export default {
  name: 'Button',
  props: {
    msg: String
  },
  methods: {
    handleClick() {
      window.location.href = "https://www.etsy.com/shop/JaneDesignStudioArt"
    }
  }
}
</script>

<style scoped>
button {
  display: inline-block;
  padding: 1rem;
  border-radius: 1rem;
  background-color: lavender;
  cursor: pointer;
  margin: 0.5rem;
  letter-spacing: 2px;
}

button:hover {
  background-color: rgb(218, 218, 255);
}
</style>