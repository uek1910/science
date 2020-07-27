<template>
	<view>
		<view class="header">
			<view class="header_item active">科研成果</view>
			<view class="header_item">专家信息</view>
			<view class="header_item">项目人才</view>
			<view class="header_item">成果视频</view>
		</view>
		<!-- 列表 -->
		<view class="reserch_list">
			<view class="reserch_listItem">
				<image src="../../static/reserch/VCG41N866011852.png" class="lists_img"></image>
				<h2 class="title">山西省科学技术厅关于印发</h2>
				<p class="content">专项基金等项目管理专业机构管理暂行规定的通知</p>
			</view>
			<view class="reserch_listItem">
				<image src="../../static/reserch/VCG41N866011852.png" class="lists_img"></image>
				<h2 class="title">山西省科学技术厅关于印发</h2>
				<p class="content">专项基金等项目管理专业机构管理暂行规定的通知</p>
			</view>
			<view class="reserch_listItem">
				<image src="../../static/reserch/VCG41N866011852.png" class="lists_img"></image>
				<h2 class="title">山西省科学技术厅关于印发</h2>
				<p class="content">专项基金等项目管理专业机构管理暂行规定的通知</p>
			</view>
			<view class="reserch_listItem">
				<image src="../../static/reserch/VCG41N866011852.png" class="lists_img"></image>
				<h2 class="title">山西省科学技术厅关于印发</h2>
				<p class="content">专项基金等项目管理专业机构管理暂行规定的通知</p>
			</view>
			<view class="reserch_listItem">
				<image src="../../static/reserch/VCG41N866011852.png" class="lists_img"></image>
				<h2 class="title">山西省科学技术厅关于印发</h2>
				<p class="content">专项基金等项目管理专业机构管理暂行规定的通知</p>
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
.header{
	width: 100%;
	height: 143rpx;
	display: flex;
     line-height: 143rpx;
	 text-align: center;
	 font-size: 26rpx;
	 color: #a3a3a3;
	 font-weight: 600;
}
.header_item{
	width: 25%;
	height: 143rpx;
	justify-content:space-between;
	position: relative;
}
.active::before{
	width: 34rpx;
	height: 4rpx;
	content: "";
	background-color: #ffab3e;
	position: absolute;
	left: 80rpx;
     top: 100rpx;
}
/* 列表 */
.reserch_list{
	width: 664rpx;
	height: auto;
	margin: 0 auto;
	overflow: hidden;
}
.reserch_listItem{
	width: 664rpx;
	height: 124rpx;
	margin-bottom: 79rpx;
	overflow: hidden;
}
.lists_img{
	width: 193rpx;
	height: 124rpx;
	float: left;
	display: block;
}
.title{
	font-size: 28rpx;
	margin-left: 227rpx;
	line-height: 56rpx;
	
}
.content{
	width: 439rpx;
	height: 68rpx;
	color:#a3a3a3;
	font-size: 24rpx;
	margin-left: 227rpx;
	line-height: 38rpx;
	text-overflow:ellipsis;
	display: -webkit-box;
	-webkit-box-orient: vertical;
	-webkit-line-clamp: 2;
	overflow: hidden;
}
</style>
