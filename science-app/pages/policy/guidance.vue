<template>
	<view class="policy_body">
		<!-- 导航开始 -->
		<view class="policy_nav">
			<view class="nav_title active">政策法规</view>
			<view class="nav_title">持续类型</view>
			<view class="nav_title">心理指导</view>
		</view>
		<!-- 导航结束 -->
		<!-- 主页图开始 -->
		<view class="policy_guidance">
			<image class="guidance_img" src="../../static/policy6.png"></image>
		</view>
		<!-- 主页图结束 -->
		<!-- btn开始 -->
		<button class="advisory" type="primary">技术咨询</button>
		<!-- btn结束 -->
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
body{
	background: #fcfcfc;
}
.policy_body{
	background: #fcfcfc;
	width: 703rpx;
	height: auto;
	overflow: hidden;
	margin: 0 auto;
}
/* 导航开始 */
.policy_nav{
	margin: 0 auto;
	font-size: #fff;
	background: #fcfcfc;
}
.nav_title{
	float: left;
	font-size: 24rpx;
	padding:64rpx 68rpx;
	color: #9597a5;
	position: relative;
}
.active ::before{
	width:17rpx;
	height: 2rpx;
	background: #ffab3e;
	color: #2c304c;
	content: "";
	position: absolute;
	top:12rpx;
	left:36rpx;
}
/* 导航结束 */
/* 主图开始 */
.policy_guidance{
	width: 658rpx;
	height: 802rpx;;
	margin: 0 auto;
	margin-bottom: 90rpx;
}
.policy_body .guidance_img{
	width: 100%;
	height:100%;
}
/* 主图结束 */
/* btn开始 */
.advisory{
	width: 702rpx;
	height: 99rpx;
	margin-top: 180rpx;
	background-color: #20c8bb;
	border-radius: 10px;
}
/* btn结束 */
</style>
