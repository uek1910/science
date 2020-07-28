<template>
	<view class="content">
		<view class="box">
			<view class="top">
				<view :class="['top_a',{top_active:state === 1}]" @click="state=1">
					A类
				</view>
				<view :class="['top_a', {top_active:state === 2}]" @click="state=2">
					B类
				</view>
			</view>
			<view class="bottom">
				<view :class="['bottom_a',{bottom_active:state === 1}]">
					<view class="bottom_list">
						<view class="bottom_t">
							已经申请的项目名称
						</view>
						<view class="bottom_t1">
							通过
						</view>
						<image src="@/static/compont/info_6.png" mode="" class="bottom_img"></image>
						<view class="bottom_t2">
							2018-10-24
						</view>
					</view>

					<view class="bottom_list">
						<view class="bottom_t">
							已经申请的项目名称
						</view>
						<view class="bottom_t1 bottom_t4">
							失败
						</view>
						<image src="@/static/compont/info_6.png" mode="" class="bottom_img"></image>
						<view class="bottom_t2">
							2018-10-24
						</view>
					</view>

					<view class="bottom_list">
						<view class="bottom_t">
							已经申请的项目名称
						</view>
						<view class="bottom_t1 bottom_t3">
							通过
						</view>
						<image src="@/static/compont/info_6.png" mode="" class="bottom_img"></image>
						<view class="bottom_t2">
							2018-10-24
						</view>
					</view>
				</view>
				<view :class="['bottom_b',{bottom_active:state === 2}]">
					<view class="bottom_list">
							<view class="bottom_t">
								已经申请的项目名称
							</view>
							<view class="bottom_t1">
								通过
							</view>
							<image src="@/static/compont/info_6.png" mode="" class="bottom_img"></image>
							<view class="bottom_t2">
								2019-10-24
							</view>
						</view>
					
						<view class="bottom_list">
							<view class="bottom_t">
								已经申请的项目名称
							</view>
							<view class="bottom_t1 bottom_t4">
								失败
							</view>
							<image src="@/static/compont/info_6.png" mode="" class="bottom_img"></image>
							<view class="bottom_t2">
								2019-10-24
							</view>
						</view>
					
						<view class="bottom_list">
							<view class="bottom_t">
								已经申请的项目名称
							</view>
							<view class="bottom_t1 bottom_t3">
								申请中
							</view>
							<image src="@/static/compont/info_6.png" mode="" class="bottom_img"></image>
							<view class="bottom_t2">
								2019-10-24
							</view>
						</view>
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				state: 1
			}
		},
		methods: {

		}
	}
</script>

<style>
	.content {
		width: 100%;
		height: 100%;
		background-color: #fefefe;
	}

	.box {
		width: 100%;
		height: auto;
		overflow: hidden;
	}

	.top {
		width: 382rpx;
		height: 182rpx;
		margin: 0 auto;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.top_a {
		width: 145rpx;
		height: 53rpx;
		line-height: 53rpx;
		text-align: center;
		color: #9294a2;
		background-color: #f8f8f8;
		font-size: 25rpx;
		border-radius: 26rpx;
	}

	.top_active {
		color: #ffffff;
		background-color: #fdab3e;
	}

	.bottom {
		width: 702rpx;
		height: 476rpx;
		margin: 0 auto;
		position: relative;
	}

	.bottom_a {
		width: 100%;
		height: 100%;
		position: absolute;
		top: 0;
		left: 0;
	}

	.bottom_b {
		width: 100%;
		height: 100%;
		position: absolute;
		top: 0;
		left: 0;
	}

	.bottom_list {
		width: 100%;
		height: 137rpx;
		box-shadow: 0px 0px 15px #f6f6f6;
		background-color: #ffffff;
		border-radius: 8rpx;
		border-bottom: 30rpx;
	}

	.bottom_t {
		width: 488rpx;
		height: 50rpx;
		padding-top: 30rpx;
		padding-left: 49rpx;
		font-size: 24rpx;
		color: #4a4c57;
		float: left;
	}

	.bottom_t1 {
		width: 76rpx;
		height: 37rpx;
		margin-left: 25rpx;
		border-radius: 18rpx;
		background-color: #20c8bb;
		line-height: 37rpx;
		text-align: center;
		font-size: 20rpx;
		color: #fff;
		float: left;
		margin: 30rpx;
	}

	.bottom_img {
		width: 9rpx;
		height: 13rpx;
		float: right;
		margin-top: 44rpx;
		margin-right: 20rpx;
	}

	.bottom_t2 {
		font-size: 18rpx;
		color: #a4a5ab;
		padding-left: 49rpx;
	}

	.bottom_t3 {
		width: 100rpx;
		margin-left: 0;
		background-color: #fdab3e;
	}

	.bottom_t4 {
		background-color: #e2e2e2;
		color: #878997;
	}

	.bottom_active {
		z-index: 10;
	}
</style>
