<template>
	<view>
		<view class="policy">
			<!-- 导航开始 -->
			<view class="top">
				<view :class="['item',{active:state===1}]" @click="state=1">
					政策法规
				</view>
				<view :class="['item',{active:state===2}]" @click="state=2">
					持续类型
				</view>
				<view :class="['item',{active:state===3}]" @click="state=3">
					心理指导
				</view>
			</view>
			<!-- 导航结束 -->
			<view class="bottom">
				<view :class="['content',{activeContent:state===1}]">
					<!-- 列表开始 -->
					<view class="policy_content">
						<view class="content1">
							<image class="content_img" src="@/static/policy/policy1.png"></image>
							<view class="con">
								<p>山西省科学技术厅关于印发《山西省省级<br>财政科技计划（专项,基金等）项目管理专<br>业机构管理暂行规定》的通知</p>
							</view>
						</view>
					</view>
					<view class="policy_content">
						<view class="content1">
							<image class="content_img" src="@/static/policy/policy2.png"></image>
							<view class="con">
								<p>山西省科学技术厅关于印发《山西省省级<br>财政科技计划（专项,基金等）项目管理专<br>业机构管理暂行规定》的通知</p>
							</view>
						</view>
					</view>
					<view class="policy_content">
						<view class="content1">
							<image class="content_img" src="@/static/policy/policy3.png"></image>
							<view class="con">
								<p>山西省科学技术厅关于印发《山西省省级<br>财政科技计划（专项,基金等）项目管理专<br>业机构管理暂行规定》的通知</p>
							</view>
						</view>
					</view>
					<view class="policy_content">
						<view class="content1">
							<image class="content_img" src="@/static/policy/policy4.png"></image>
							<view class="con">
								<p>山西省科学技术厅关于印发《山西省省级<br>财政科技计划（专项,基金等）项目管理专<br>业机构管理暂行规定》的通知</p>
							</view>
						</view>
					</view>
					<view class="policy_content">
						<view class="content1">
							<image class="content_img" src="@/static/policy/policy1.png"></image>
							<view class="con">
								<p>山西省科学技术厅关于印发《山西省省级<br>财政科技计划（专项,基金等）项目管理专<br>业机构管理暂行规定》的通知</p>
							</view>
						</view>
					</view>
				</view>
				<!-- 列表结束 -->
				<view :class="['content',{activeContent:state===2}]">
					<!-- 列表2开始-->
					<view class="policy_content2">
						<view class="content2">
							<h1>高薪企业认证</h1>
							<image class="content2_img" src="@/static/policy/policy7.png"></image>
						</view>
						<view class="content2">
							<h1>研发补助</h1>
							<image class="content2_img" src="@/static/policy/policy5.png"></image>
						</view>
						<view class="content2">
							<h1>研发加计</h1>
							<image class="content2_img" src="@/static/policy/policy8.png"></image>
						</view>
					</view>
				</view>
				<!-- 列表2结束 -->
				<view :class="['content',{activeContent:state===3}]">
					<!-- 主页图开始 -->
					<view class="policy_guidance">
						<image class="guidance_img" src="@/static/policy/policy6.png"></image>
					</view>
					<!-- 主页图结束 -->
					<!-- btn开始 -->
					<button class="advisory" type="primary">技术咨询</button>
					<!-- btn结束 -->
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
	.policy {
		width: 703rpx;
		height: auto;
		overflow: hidden;
		margin: 0 auto;
	}
	.top {
		width: 703rpx;
		height: 149rpx;
		font-size: #fff;
		background: #fcfcfc;
		display: flex;
		justify-content: space-between;
	}
	.item {
		width: 200rpx;
		height: 149rpx;
		line-height: 149rpx;
		text-align: center;
		font-size: 24rpx;
		color: #9597a5;
		position: relative;
	}
	.active {
		color: #000;
	}
	.active::after {
		content: "";
		width: 34rpx;
		height: 4rpx;
		background: #ffab3e;
		position: absolute;
		top: 100rpx;
		left: 80rpx;
	}
	.bottom {
		width: 700rpx;
		height: 1012rpx;
		position: relative;
	}
	.content {
		width: 700rpx;
		height: auto;
		position: absolute;
		left: 0;
		top: 0;
		background: #fff;
		text-align: center;
		display: none;
	}
	.activeContent {
		z-index: 1;
		display: block;
	}
	/* 列表结束 */
	.policy_content {
		width: 703rpx;
		height: auto;
		border-radius: 2rpx;
		margin: 0 auto;
	}
	.content1 {
		width: 700rpx;
		height: 179rpx;
		background: #fff;
		margin-bottom: 26rpx;
		float: left;
		box-shadow: 0rpx 1rpx 16rpx 0rpx rgba(229, 229, 229, 0.75);
	}
	.content_img {
		width: 193rpx;
		height: 126rpx;
		float: left;
		margin: 26rpx 9rpx;
	}
	.con {
		width: 487rpx;
		height: 177rpx;
		float: right;
		margin: 26rpx 0rpx;
		font-size: 22rpx;
		/* color: #2C405A; */
	}
	.con p{
		color: #7f7f7f;
		margin-left: 32rpx;
		text-align: left;
	}
	.policy_content2 {
		width: 703rpx;
		height: auto;
		border-radius: 2rpx;
		margin: 0 auto;
	}
	.content2 {
		width: 700rpx;
		height: 179rpx;
		background: #fff;
		margin-bottom: 26rpx;
		float: left;
		box-shadow: 0rpx 1rpx 16rpx 0rpx rgba(229, 229, 229, 0.75);
	}
	.content2 h1 {
		display: block;
		float: left;
		padding-top: 80rpx;
		padding-left: 53rpx;
		font-size: 32rpx;
		color: #2b3787;;
	}
	.content2_img {
		width: 130rpx;
		height: 130rpx;
		float: right;
		margin: 33rpx 60rpx 29rpx;
	}
	/* 列表结束 */
	/* 主图开始 */
	.policy_guidance {
		width: 658rpx;
		height: 802rpx;
		margin: 0 auto;
		margin-bottom: 90rpx;
	}
	.guidance_img {
		width: 100%;
		height: 100%;
	}
	/* 主图结束 */
	/* btn开始 */
	.advisory {
		width: 702rpx;
		height: 99rpx;
		margin: 0 auto;
		background-color: #20c8bb;
		border-radius: 10px;
	}
	/* btn结束 */
</style>
