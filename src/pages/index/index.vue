<template>
  <view class="content">
    <view class="placeholder">
      <text class="title">主页</text>
      <text class="subtitle">这是一个空白的主页占位符</text>
    </view>
  </view>
</template>

<script setup lang="ts">
// 主页逻辑
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #f5f5f5;
}

.placeholder {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 40rpx;
  background-color: #ffffff;
  border-radius: 20rpx;
  box-shadow: 0 2rpx 10rpx rgba(0, 0, 0, 0.1);
}

.title {
  font-size: 48rpx;
  color: #333333;
  margin-bottom: 20rpx;
  font-weight: bold;
}

.subtitle {
  font-size: 28rpx;
  color: #666666;
  text-align: center;
}
</style>
