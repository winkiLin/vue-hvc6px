<template>
  <div id="index">
    <p v-for="(value, key) in item" :key="key">{{ value }}</p>
    <button @click="addNew">添加新的属性</button>
  </div>
</template>

<script>
export default {
  name: 'index',
  data() {
    return {
      item: {
        oldProperty: '旧的属性',
      },
    };
  },
  methods: {
    addNew() {
      this.item.newProperty = '新的属性';
      console.log(this.item, '查看');
    },
  },
  components: {},
};
</script>

<style lang="css" scoped>
#index {
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
