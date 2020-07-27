<template>
	<view>
		<!-- 标题选项卡 -->
		<view class="tit">
			<view class="list active" @click="handleTab(index)">企业信息</view>
			<view class="list">知识产权</view>
			<view class="list">设计方案</view>
			<view class="list">需求方案</view>
			<view class="list">技术需求</view>
			<view class="list">设备共享</view>
		</view>
		<!-- 内容方案 -->
		<view class="content">
			<!-- 企业信息 -->
			<view class="way xinxi">
				<view class="info">
					<view class="bt">太阳能发电项目需求</view>
					<view class="jianjie">企业简介</view>
					<view class="text">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划（专项、基金等）项目管理专业机构管理暂行规定》</view>
					<view class="text">经厅际联席会审定并经法制办审查通过，现正式印发请认真执行。附件：《山西省省级财政科技计划（专项、基金等）项目管理专业机构管理暂行规定》</view>
					<view class="name">山西省科学技术厅</view>
					<view class="date">2018-10-24</view>
				</view>
				<view class="btn">查看更多</view>
			</view>
			<!-- 知识产权 -->
			<view class="way" style="display: none;">
				<view class="plan">
					<view class="left">
						<view class="line"></view>
						<view>查看申请结果</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<view class="line"></view>
						<view>申请评估结果</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
			</view>
			<!-- 设计方案 -->
			<view class="way" style="display: none;">
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/wj.png" mode=""></image>
						<view>定制方案</view>
					</view>
					<view class="right">
						<view class="ff">付费</view>
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/wx1.png" mode=""></image>
						<view>已有方案一</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/wx1.png" mode=""></image>
						<view>已有方案二</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
			</view>
			<!-- 需求方案 -->
			<view class="way" style="display: none;">
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/wj.png" mode=""></image>
						<view>需求方案</view>
					</view>
					<view class="right">
						<view class="ff">付费</view>
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/wx1.png" mode=""></image>
						<view>已有方案一</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/wx1.png" mode=""></image>
						<view>已有方案二</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
			</view>
			<!-- 技术需求 -->
			<view class="way" style="display: none;">
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/fabu.png" mode=""></image>
						<view>已发布</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/qiye.png" mode=""></image>
						<view>企业一</view>
					</view>
					<view class="right">
						<view class="ff">付费</view>
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/qiye.png" mode=""></image>
						<view>企业二</view>
					</view>
					<view class="right">
						<view class="ff">付费</view>
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
			</view>
			<!-- 设备共享 -->
			<view class="way" style="display: none;">
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/fabu.png" mode=""></image>
						<view>已发布</view>
					</view>
					<view class="right">
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/qiye.png" mode=""></image>
						<view>企业一</view>
					</view>
					<view class="right">
						<view class="ff">付费</view>
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
					</view>
				</view>
				<view class="plan">
					<view class="left">
						<image src="@/static/compony/qiye.png" mode=""></image>
						<view>企业二</view>
					</view>
					<view class="right">
						<view class="ff">付费</view>
						<image src="@/static/compony/fanhui-2.png" mode=""></image>
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
				index:0
			}
		},
		methods: {
			handleTab(){
				alert(1)
			}
		}
	}
</script>

<style>
	/* 标题 */
	.tit{
		width: 100%;
		height: auto;
		overflow: hidden;
		padding: 43rpx 24rpx 19rpx;
		box-sizing: border-box;
		display: flex;
		flex-wrap: wrap;
	}
	.tit .list{
		min-width: 144rpx;
		padding: 0 20rpx;
		box-sizing: border-box;
		height: 52rpx;
		line-height: 52rpx;
		border: 2rpx solid #f2f3f4;
		background: #f8f8f8;
		color: #9294a2;
		font-size: 26rpx;
		margin: 0 42rpx 43rpx;
		position: relative;
		border-radius: 26rpx;
	}
	.tit .list:not(:nth-child(3n))::after{
		content: "";
		position: absolute;
		top: 20rpx;
		right: -42rpx;
		width: 2rpx;
		height: 16rpx;
		background: #e9e9e9;
	}
	.tit .list.active{
		background: #fdab3e;
		color: #fff;
		border-color: #fdab3e;
	}
	/* 内容方案 */
	.content{
		width: 100%;
		padding: 0 24rpx;
		box-sizing: border-box;
		height: auto;
	}
	.way{
		width: 100%;
		height: auto;
		background: #fcfcfc;
	}
	.plan{
		width: 100%;
		height: 101rpx;
		border-radius: 8rpx;
		box-shadow:0rpx 0rpx 15rpx #eee;
		display: flex;
		justify-content: space-between;
		background: #fff;
		line-height: 101rpx;
		margin-bottom: 20rpx;
	}
	.plan .left{
		margin-left: 27rpx;
		display: flex;
		color: #4a4c57;
		font-size: 28rpx;
	}
	.plan .left image{
		width: 53rpx;
		height: 43rpx;
		margin-right: 32rpx;
		padding-top: 29rpx;
	}
	.plan .right{
		margin-right: 43rpx;
		display: flex;
		height: 100%;	
	}
	.plan .right .ff{
		width: 75rpx;
		height: 36rpx;
		margin-top: 33rpx;
		border-radius: 18rpx;
		background: #20c8bb;
		font-size: 22rpx;
		color: #fff;
		line-height: 36rpx;
		text-align: center;
		margin-right: 21rpx;
	}
	.plan .right image{
		width: 8rpx;
		height: 13rpx;
		padding-top: 44rpx;
	}
	/* 简介 */
	.xinxi{
		background: none;
		border-radius: 8rpx;
	}
	.info{
		width: 100%;
		padding: 46rpx 44rpx 58rpx;
		box-shadow:0rpx 0rpx 15rpx #eee;
		box-sizing: border-box;
		height: auto;
	}
	.info .bt{
		font-size: 44rpx;
		color: #4a4c57;
		height: 88rpx;
	}
	.info .jianjie{
		color: #a5a7af;
		font-size: 28rpx;
		height: 62rpx;
	}
	.info .text{
		font-size: 24rpx;
		color: #2c304c;
		line-height: 34rpx;
		margin-bottom: 40rpx;
	}
	.info .name{
		margin-top: 68rpx;
		color: #4a4c57;
		font-size: 24rpx;
		height: 36rpx;
		text-align: right;
	}
	.info .date{
		color: #4a4c57;
		text-align: right;
		font-size: 26rpx;
	}
	.xinxi .btn{
		margin-top: 67rpx;
		width: 100%;
		height: 99rpx;
		background: #20c8bb;
		text-align: center;
		line-height: 99rpx;
		color: #fff;
		font-size: 26rpx;
		border-radius: 8rpx;
	}
	.way .line{
		width: 5rpx;
		height: 22rpx;
		background: #fdab3e;
		margin-left: -27rpx;
		margin-top: 39rpx;
		margin-right: 40rpx;
	}
</style>
