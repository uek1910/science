<template>
	<view class="body">
		<view class="title">
			<view @click="chage=0" class="act" :class="{'chage':chage===0}">
				动态信息
			</view>
			<view class="int"></view>
			<view @click="chage=1" class="info" :class="{'chage':chage===1}">
				活动主题	
			</view>
		</view>
		<view class="info-content" v-show="chage===0">
			<view class="info-contentlist">
				<image src="../../static/actvity/img/back.png" class="info-contentlist-imga"></image>
				<view class="info-contentlist-text">
					省科技厅召开严肃行政审批窗口
				</view>
				
				<view class="info-contentlist-time">
					2018-10-24
				</view>
			</view>
		</view>
		<view class="act-content" v-show="chage===1">
			<view class="act-contentlist">
				<image src="../../static/actvity/img/back.png" class="info-contentlist-imga"></image>
				<view class="act-contentlist-text">
					省科技厅召开严肃行政审批窗口
				</view>
				<view class="act-contentlist-time">
					2018-10-24
				</view>
				<image src="../../static/actvity/img/bg.png" class="act-contentlist-img"></image>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				chage:0
			}
		},
		methods: {

		}
	}
</script>

<style>
	.body{
		margin-top: 38rpx;
	}
	.body .title{
		width: 400rpx;
		height: 56rpx;
		margin: 0 auto;
		margin-bottom: 40rpx;
	}
	.body .title .info{
		width: auto;
		height: 56rpx;
		line-height: 56rpx;
		text-align: center;
		color: #9193a2;
		background-color: #f8f8f8;
		border: 2px solid #f2f3f4;
		border-radius: 40rpx;
		float: left;
		font-size: 26rpx;
		padding-left: 22rpx;
		padding-right: 22rpx;
	}
	.body .title .int{
		width: 2rpx;
		height: 16rpx;
		margin-top: 20rpx;
		margin-left: 42rpx;
		margin-right: 42rpx;
		float: left;
		background-color: #e9e9e9;
	}
	.body .title .act{
		width: auto;
		height: 56rpx;
		line-height: 56rpx;
		text-align: center;
		color: #9193a2;
		background-color: #f8f8f8;
		border: 2px solid #f2f3f4;
		border-radius: 40rpx;
		float: left;
		padding-left: 22rpx;
		padding-right: 22rpx;
		font-size: 26rpx;
	}
	.body .title .chage{
		background-color: #ffac2d;
		color: #fff;
	}
	.body .info-content{
		margin-left: 23rpx;
		margin-right: 25rpx;
	}
	.body .info-content .info-contentlist{
		width: 612rpx;
		height: auto;
		padding-left: 47rpx;
		padding-right: 43rpx;
		padding-top: 37rpx;
		padding-bottom: 36rpx;
		font-family: PingFangSC-Regular, sans-serif;
		box-shadow: 0rpx 1rpx 16rpx 0rpx rgba(229, 229, 229, 0.75);
		overflow: hidden;
	}
	.body .info-content .info-contentlist .info-contentlist-text{
		margin-bottom: 26rpx;
		font-size: 26rpx;
	}
	.body .info-content .info-contentlist .info-contentlist-imga{
		width: 7rpx;
		height: 13rpx;
		float: right;
		margin-top: 10rpx;
	}
	.body .info-content .info-contentlist .info-contentlist-time{
		font-size: 26rpx;
		color: #a4a5ab;
	}
	.body .act-content{
		margin-left: 23rpx;
		margin-right: 25rpx;
	}
	.body .act-content .act-contentlist{
		width: 612rpx;
		height: auto;
		padding-left: 47rpx;
		padding-right: 43rpx;
		padding-top: 37rpx;
		padding-bottom: 36rpx;
		background-color: #ffffff;
		box-shadow: 0rpx 1rpx 16rpx 0rpx rgba(229, 229, 229, 0.75);
		border-radius: 10rpx;
	}
	.body .act-content .act-contentlist .info-contentlist-imga{
		width: 7rpx;
		height: 13rpx;
		float: right;
		margin-top: 10rpx;
	}
	.body .act-content .act-contentlist .act-contentlist-text{
		margin-bottom: 26rpx;
		font-size: 26rpx;
	}
	.body .act-content .act-contentlist .act-contentlist-time{
		font-size: 26rpx;
		color: #a4a5ab;
	}
	.body .act-content .act-contentlist .act-contentlist-img{
		width: 622rpx;
		height: 253rpx;
		margin-top: 22rpx;
	}
</style>
