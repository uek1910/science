<template>
	<view class="policy_body">
		<view class="policy_nav">
			<view class="nav_title active">政策法规</view>
			<view class="nav_title">持续类型</view>
			<view class="nav_title">心理指导</view>
		</view>
		<view class="policy_content">
			<view class="content">
				<image class="content_img" src="../../static/logo.png"></image>
				<view class="con">
					<p>山西省科学技术厅关于印发《山西省省级<br>财政科技计划（专项,基金等）项目管理专<br>业机构管理暂行规定》的通知</p>
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
.policy_nav{
	/* width: 703rpx;
	height: 177rpx; */
	/* padding:  0 24rpx; */
	margin: 0 auto;
	font-size: #fff;
	background: #fcfcfc;
}
.nav_title{
	float: left;
	font-size: 24rpx;
	padding:64rpx 68rpx;
	color: #9597a5;
}
.active ::before{
	width: 34rpx;
	height: 4rpx;
	background: #ffab3e;
	color: #2c304c;
}
.policy_content{
	width: 703rpx;
	height: 1020rpx;
	border-radius:2rpx;
	margin: 0 auto;
}
.content{
	width: 700rpx;
	height: 179rpx;
	background: #fff;
	margin-bottom: 26rpx;
	float: left;
	box-shadow: 0rpx 0rpx 10rpx #000;
}
.content_img{
	width:193rpx;
	height:126rpx;
	float: left;
	margin: 26rpx 9rpx;
}
.con{
	width: 487rpx;
	height: 177rpx;
	float: right;
	margin: 26rpx 0rpx;
}
.con{
	font-size: 22rpx;
	color: #7f7f7f;
}






</style>
