<template>
  <div id="tab-bar">
   <slot></slot>
  </div>
</template>

<script>
  export default {
    name: "TabBar"
  }
</script>

<style scoped>
  #tab-bar{
    position: fixed;
    bottom: 0;
    height: 55px;
    left: 0;
    right: 0;
    display: flex;
    text-align: center;
    background: #ccc;
  }
  .tab-bar-item{
    margin-top: 5px;
    flex: 1;
  }
  #tab-bar .item-icon{
    font-size: 26px;
  }

</style>