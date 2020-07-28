<template>
	<view>
		<view class="list">
			<view class="content">
				<view class="tit">太阳能发电项目需求</view>
				<view class="fast">紧急</view>
				<view class="info">
					<view class="name">需求单位：</view>
					<view class="zhi">山西省科技局</view>
				</view>
				<view class="info">
					<view class="name">需求地址：</view>
					<view class="zhi">山西省太原市迎泽区府西街128号</view>
				</view>
				<view class="info">
					<view class="name">联 系 人 ：</view>
					<view class="zhi">苏灿灿</view>
				</view>
				<view class="info">
					<view class="name">电子邮箱：</view>
					<view class="zhi">1536839@163.com</view>
				</view>
			</view>
			<view class="text">
				<view class="title">需求描述</view>
				<view class="nr">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划（专项、基金等）项目管理专业机构管理暂行规定》</view>
				<view class="nr">经厅际联席会审定并经法制办审查通过，现正式印发请认真执行。附件：《山西省省级财政科技计划（专项、基金等）项目管理专业机构管理暂行规定》</view>
				<view class="name">山西省科学技术厅</view>
				<view class="date">2018-10-24</view>
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
	}
	.list .content{
		width: 100%;
		box-sizing: border-box;
		padding: 0 47rpx 71rpx;
		box-shadow: 0rpx 0rpx 15rpx #eee;
	}
	.list .content .tit{
		color: #4a4c57;
		font-size: 44rpx;
		padding-top: 44rpx;
	}
	.list .content .fast{
		width: 74rpx;
		height: 36rpx;
		text-align: center;
		line-height: 36rpx;
		color: #fff;
		font-size: 22rpx;
		background: #20c8bb;
		border-radius: 18rpx;
		margin-top: 21rpx;
		margin-bottom: 65rpx;
	}
	.list .content .info{
		display: flex;
		height: 61rpx;
	}
	.list .content .info .name{
		color: #a5a7af;
		font-size: 28rpx;
		padding-left: 28rpx;
		position: relative;
		margin-top: 0;
	}
	.list .content .info .name::before{
		content: "";
		position: absolute;
		top: 16rpx;
		left: 0;
		width: 12rpx;
		height: 5rpx;
		background: #fdab3e;
	}
	.list .content .info .zhi{
		color: #4a4c57;
		font-size: 28rpx;
	}
	.list .text{
		padding: 60rpx 47rpx 0;
	}
	.list .text .title{
		color: #a5a7af;
		font-size: 28rpx;
		height: 62rpx;
	}
	.list .text .nr{
		font-size: 24rpx;
		color: #2c304c;
		line-height: 34rpx;
		margin-bottom: 40rpx;
	}
	.list .name{
		margin-top: 68rpx;
		color: #4a4c57;
		font-size: 24rpx;
		height: 36rpx;
		text-align: right;
	}
	.list .date{
		color: #4a4c57;
		text-align: right;
		font-size: 26rpx;
	}
</style>
