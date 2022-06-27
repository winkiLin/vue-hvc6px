<template>
  <div id="index">
    <div class="part">
      <a href="https://stackblitz.com/">
        <img
          src="https://avatars.githubusercontent.com/u/28103559?s=160&v=4"
          alt="logo"
        />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'index',
  components: {},
};
</script>

<style lang="css" scoped>
#index {
  border: 1px solid red;
  min-height: 100vh;
  padding: 20px;
}
#index .part {
  width: 100px;
  height: 100px;
  background: black;
  border-radius: 20px;
  border: 1px solid #d7d7d7;
}
</style>
