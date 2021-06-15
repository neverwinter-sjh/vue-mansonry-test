<template>
  <div :default="{item}">
    <div class="Item">
      <img :src="item.image" />

      <div class="Content">
        <h5 class="text-ellipsis-1l">{{item.title}}</h5>
        <p class="text-ellipsis-2l">{{item.content}}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ImageItem',
  props: {
    item: Object
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
