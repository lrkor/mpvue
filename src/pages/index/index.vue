<template>
  <div>
    <button type="primary" @click="handClick">这是一个按钮</button>
    <i-icon type="activity" size="28" color="#80848f"></i-icon>
    <i-card full title="卡片标题" extra="额外内容" thumb="https://i.loli.net/2017/08/21/599a521472424.jpg">
      <view slot="content">内容不错</view>
      <view slot="footer">尾部内容</view>
    </i-card>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        userInfo: {}
      };
    },
    methods:{
      handClick(){
        console.log(111);
      }
    }
  };
</script>

<style scoped>

</style>
