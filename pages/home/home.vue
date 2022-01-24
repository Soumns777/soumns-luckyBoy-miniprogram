<template>
  <view class="container">
     		<!-- <u-navbar :is-back="true" title="首页">
     	 	<view class="slot-wrap">
     			首页
     			</view> 
     		</u-navbar> -->
        <u-button type="primary">主要按钮</u-button>
        <u-button type="success">成功按钮</u-button>
        <u-button type="info">信息按钮</u-button>
        <u-button type="warning">警告按钮</u-button>
        <u-button type="error">危险按钮</u-button>
        777
  </view>
</template>

<script>
</script>

<style lang="scss" scoped>
  .slot-wrap {
  		display: flex;
  		align-items: center;
  		/* 如果您想让slot内容占满整个导航栏的宽度 */
  		/* flex: 1; */
  		/* 如果您想让slot内容与导航栏左右有空隙 */
  		/* padding: 0 30rpx; */
  	}
</style>
