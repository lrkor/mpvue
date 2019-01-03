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
  .userinfo {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .userinfo-avatar {
    width: 128 rpx;
    height: 128 rpx;
    margin: 20 rpx;
    border-radius: 50%;
  }

  .userinfo-nickname {
    color: #aaa;
  }

  .usermotto {
    margin-top: 150px;
  }

  .form-control {
    display: block;
    padding: 0 12px;
    margin-bottom: 5px;
    border: 1px solid #ccc;
  }

  .counter {
    display: inline-block;
    margin: 10px auto;
    padding: 5px 10px;
    color: blue;
    border: 1px solid blue;
  }
</style>
