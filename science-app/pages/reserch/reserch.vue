<template>
	<view>
		<view class="header">
			<view class="header_item" @click="act=0" :class="{'active':act===0}">科研成果</view>
			<view class="header_item"  @click="act=1" :class="{'active':act===1}">专家信息</view>
			<view class="header_item"   @click="act=2" :class="{'active':act===2}">项目人才</view>
			<view class="header_item">成果视频</view>
		</view>
		<!-- 列表 -->
		<view class="reserch_list" v-show="act===0">
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
		<!-- 专家信息 -->
		<view class="expert" v-show="act===1">
			<view class="expertList">
				<image class="expertImg" src="../../static/reserch/VCG41N866011852.png"></image>
				<view class="expert_box">
				<h2 class="expert_name">苏灿</h2>
				<h4 class="expert_content"><span>简介：</span>高级技术员高级技术员</h4>
				</view>
				<view class="expertBtn">研究生</view>
			</view>
			<view class="expertList">
				<image class="expertImg" src="../../static/reserch/VCG41N866011852.png"></image>
				<view class="expert_box">
				<h2 class="expert_name">苏灿</h2>
				<h4 class="expert_content"><span>简介：</span>高级技术员高级技术员</h4>
				</view>
				<view class="expertBtn">研究生</view>
			</view>
			<view class="expertList">
				<image class="expertImg" src="../../static/reserch/VCG41N866011852.png"></image>
				<view class="expert_box">
				<h2 class="expert_name">苏灿</h2>
				<h4 class="expert_content"><span>简介：</span>高级技术员高级技术员</h4>
				</view>
				<view class="expertBtn">研究生</view>
			</view>
		</view>
		<!-- 项目人才 -->
		<view class="expert" v-show="act===2">
			<view class="expertList">
				<image class="expertImg" src="../../static/reserch/VCG41N866011852.png"></image>
				<view class="expert_box">
				<h2 class="expert_name">苏灿</h2>
				<h4 class="expert_content"><span>简介：</span>高级技术员高级技术员</h4>
				</view>
				<view class="expertBtn">研究生</view>
			</view>
			<view class="expertList">
				<image class="expertImg" src="../../static/reserch/VCG41N866011852.png"></image>
				<view class="expert_box">
				<h2 class="expert_name">苏灿</h2>
				<h4 class="expert_content"><span>简介：</span>高级技术员高级技术员</h4>
				</view>
				<view class="expertBtn">研究生</view>
			</view>
			<view class="expertList">
				<image class="expertImg" src="../../static/reserch/VCG41N866011852.png"></image>
				<view class="expert_box">
				<h2 class="expert_name">苏灿</h2>
				<h4 class="expert_content"><span>简介：</span>高级技术员高级技术员</h4>
				</view>
				<view class="expertBtn">研究生</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				act:0
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
/* 专家信息 */
.expert{
	width: 703rpx;
	height: auto;
	margin: 0 auto;
	overflow: hidden;
}
.expertList{
	width: 703rpx;
	height: 154rpx;
	border-top: 1px solid #f6f6f6;
		border-bottom: 1px solid #f6f6f6;
}
.expertImg{
	border-radius: 50%;
	width: 120rpx;
	height: 120rpx;
	float: left;
	margin-top: 20rpx;
}
.expert_name{
	float: left;
	margin-left: 29rpx;
	margin-top: 38rpx;
	font-size: 28rpx;
}
.expert_box{
	width: 420rpx;
	height: auto;
	float: left;
}
.expert_content{
	margin-left: 29rpx;
	margin-top: 80rpx;
	font-size: 28rpx;
	text-overflow:ellipsis;
	display: -webkit-box;
	-webkit-box-orient: vertical;
	-webkit-line-clamp: 1;
	overflow: hidden;
	
}
.expertBtn{
	width:96rpx;
	height: 38rpx;
	float: right;
	text-align: center;
	line-height: 38rpx;
	background-color: #e8f9f8;
	color: #46d1c6;
	margin-top: 63rpx;
	border-radius: 23rpx;
	font-size: 22rpx;
}
</style>
