<template>
  <div class="myHeader">
    <img class="logo" src="../assets/logo1.png" />
    <h3 class="title">Minoz Store</h3>
  </div>
</template>

<script>
  export default {
    name:"myHeader",
    data(){
      return{
        msg:"welcome to Your Vue.js App"
      };
    }
  };
</script>

<!--Add "scoped" attribute to limit CSS to this compontent only-->
<style lang="less" scoped>
.myHeader {
  display: flex;
  flex-direction: row;
  align-items: center;
  background: rgba(0,0,0,0.15);
  .logo {
    width: 50px;
    height: 50px;
    margin-right: 10px;
    margin-left: 5px;
  }
  .title {
    padding: 0;
    margin: 0;
    font-size: 16px;
    color: #fff;
  }
}
</style>
