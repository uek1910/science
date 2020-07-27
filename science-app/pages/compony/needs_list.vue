<template>
	<view>
		<view class="list">
			<view class="content">
				<view class="left">
					<view class="tit">太阳能发电需求</view>
					<view class="fast">紧急</view>
				</view>
				<view class="right">
					<view class="date">2018-10-24</view>
					<image src="@/static/compony/fanhui-2.png" mode=""></image>
				</view>
			</view>
			<view class="content">
				<view class="left">
					<view class="tit">新风净化机通过在墙上的通风管...</view>
					<view class="fast yb">一般</view>
				</view>
				<view class="right">
					<view class="date">2018-10-24</view>
					<image src="@/static/compony/fanhui-2.png" mode=""></image>
				</view>
			</view>
			<view class="content">
				<view class="left">
					<view class="tit">太阳能发电需求</view>
					<view class="fast">紧急</view>
				</view>
				<view class="right">
					<view class="date">2018-10-24</view>
					<image src="@/static/compony/fanhui-2.png" mode=""></image>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.list{
		width: 100%;
		padding:  36rpx 24rpx 0;
		box-sizing: border-box;
		height: auto;
		overflow: hidden;
	}
	.list .content{
		width: 100%;
		height: 172rpx;
		box-shadow: 0rpx 0rpx 15rpx #eee;
		display: flex;
		justify-content: space-between;
		margin-bottom: 24rpx;
	}
	.list .content .left{
		margin-left: 44rpx;
		height: 100%;
		width: 64%;
		overflow: hidden;
		text-overflow: ellipsis;
		white-space: nowrap;
	}
	.list .content .left .tit{
		padding-top: 44rpx;
		height: 48rpx;
		font-size: 28rpx;
		color: #4a4c57;
	}
	.list .content .left .fast{
		width: 74rpx;
		height: 36rpx;
		text-align: center;
		line-height: 36rpx;
		color: #fff;
		font-size: 22rpx;
		background: #20c8bb;
		border-radius: 18rpx;
	}
	.list .content .left .yb{
		background: #fdab3e;
	}
	.list .content .right{
		margin-right: 37rpx;
		height: 100%;
	}
	.list .content .right .date{
		padding-top: 54rpx;
		color: #a4a5ab;
		font-size: 26rpx;
	}
	.list .content .right image{
		width: 8rpx;
		height: 13rpx;
		position: relative;
		right: -130rpx;
		margin-top: 44rpx;
	}
</style>
