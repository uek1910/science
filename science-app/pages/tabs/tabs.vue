<template>
	<view>
		<view class="tabs">
			<view class="top">
				<view :class="['item',{active:state===1}]" @click="state=1">
					1
				</view>
				<view :class="['item',{active:state===2}]" @click="state=2">
					2
				</view>
				<view :class="['item',{active:state===3}]" @click="state=3">
					3
				</view>
			</view>
			<view class="bottom">
				<view :class="['content',{activeContent:state===1}]">
					内容1
				</view>
				<view :class="['content',{activeContent:state===2}]">
					内容2
				</view>
				<view :class="['content',{activeContent:state===3}]">
					内容3
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
               state:1
			}
		},
		methods: {

		}
	}
</script>

<style>
	.tabs {
		width: 700rpx;
		height: 500rpx;
		margin: 0 auto;
		border: 1rpx solid red;
	}

	.top {
		width: 700rpx;
		height: 100rpx;
		display: flex;
		justify-content: space-between;
	}

	.item {
		width: 200rpx;
		height: 100rpx;
		text-align: center;
	}

	.active {
		color: red;
	}

	.bottom {
		width: 700rpx;
		height: 400rpx;
		position: relative;
	}

	.content {
		width: 700rpx;
		height: 400rpx;
		position: absolute;
		left: 0;
		top: 0;
		background: #fff;
		text-align: center;
		line-height: 400rpx;
	}
	
	.activeContent{
		z-index:1;
	}
</style>
