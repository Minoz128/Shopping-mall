<template>
  <div class="activity">
    <h3 class="title">活动推荐</h3>
    <div class="content">
      <div class="content_item" v-for="(item,index) in items" :key="index">
        <img src="../../static/carousel3.png" alt="">
        <p class="name">品牌:Minoz</p>
        <p class="desc">仅展示，不出售</p>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: "activity",
    data() {
      return {
        items: [1, 2]
      };
    },
    mounted() {}
  };
</script>

<style lang="less" scoped>
  .activity {
    background: #eee;
    .title {
      width: 100%;
      height: 50px;
      line-height: 50px;
      text-align: center;
      color: gray;
      border-bottom: 1px solid #000;
      background: #fff;
    }
    .content {
      .content_item {
        background: #fff;
        margin-bottom: 10px;
        img {
          width: 100%;
          height: 220px;
        }
      }
      .name {
        font-size: 15px;
        color: #000;
        margin-bottom: 5px;
      }
      .desc {
        font-size: 13px;
        color: #000;
      }
    }
  }
</style>
