<template>
  <button class="button" :innerText="msg" v-on:click="handleClick">
  </button>
</template>

<script>
export default {
  name: 'Instagram',
  props: {
    msg: String
  },
  methods: {
    handleClick() {
      window.location.href = "https://www.instagram.com/jane_designstudio/"
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
  height: 3rem;
  width: 3rem;
  padding: 1rem;
  background-image: url('../assets/insta.png');
  background-size: 100%;
  margin: 0.5rem;
}

button:hover {
  background-color: rgb(218, 218, 255);
}
</style>