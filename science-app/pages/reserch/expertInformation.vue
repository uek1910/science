<template>
	<view>
		<view class="infor_box">
			<image class="inforImg" src="../../static/reserch/VCG41N866011852.png"></image>
		
			<view class="infor_content">
				<view class="infor_top">
					<h1 class="infor_name">苏灿</h1>
					<view class="expertBtns">博士</view>
				</view>
				<view class="address">
					<image class="addressIcon" src="../../static/reserch/2df268292fb39f12cf7ada53f84607c.png"></image>
					<p class="addressName">单位名称:<span class="sheng"> 山西省科技局</span></p>
				</view>
				<view class="address">
					<image class="addressIcon" src="../../static/reserch/f8fde3416f3e112def320ac01a32e1c.png"></image>
					<p class="addressName">行业领域:<span class="sheng">环境保护</span></p>
				</view>
				<view class="address">
					<image class="addressIcon" src="../../static/reserch/fe28ba69f7f1bd38f0e0c8950e4141c.png"></image>
					<p class="addressName">专业特长:<span class="sheng">节能减排  温室效应</span></p>
				</view>
				
			</view>
		</view>
	     <!-- 项目介绍 -->
	     <view class="project">
	     	<h1 class="project_title">主要成就</h1>
	     	<p class="project_content">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划》</p>
	     		<p class="project_content">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划》</p>
	     </view>
	</view>
</template>

<script>
</script>

<style>
	.infor_box{
		width: 690rpx;
		height: 408rpx;
		margin:0 auto;
		border-bottom: 1rpx solid #f7f7f7;
	}
	.inforImg{
		float: left;
		margin-top: 37rpx;
		width: 244rpx;
		height: 303rpx;
	}
	.infor_content{
		width:370rpx;
		height: 303rpx;
		margin-top: 38rpx;
		float: right;
	}
	
	.infor_top{
		width: 370rpx;
		height: 106rpx;
	}
	.infor_name{
		float: left;
		font-size:38rpx;
		margin-top: 36rpx;
	}
	.expertBtns{
		width:96rpx;
		height: 38rpx;
		float: left;
		text-align: center;
		line-height: 38rpx;
		background-color: #e8f9f8;
		color: #46d1c6;
		border-radius: 23rpx;
		font-size: 22rpx;
		margin-top: 40rpx;
		margin-left: 19rpx;
	}
   .address{
	   width: 370rpx;
	   height: 65rpx;
   }
   .addressIcon{
	   width: 22rpx;
	   height: 22rpx;
	   float: left;
	   margin-top: 24rpx;
   }
   .addressName{
	   float: left;
	   font-size: 24rpx;
	   line-height: 65rpx;
	   margin-left: 10rpx;
	   text-overflow:ellipsis;
	   display: -webkit-box;
	   -webkit-box-orient: vertical;
	   -webkit-line-clamp: 1;
	   overflow: hidden;
   }
   .addressName .sheng{
	   color: #d1d2d4;
	   padding-left: 10rpx;
   }
   /* 主要成就 */
   .project{
   	width: 619rpx;
   	height: auto;
   	margin: 0 auto;
   			margin-top: 43rpx;
   
   }
   .project_title{
   	font-size: 28rpx;
   	line-height: 90rpx;
   	color: #c7c8cd;
   	font-weight: 400rpx;
   }
   .project_content{
   	font-size: 24rpx;
   	line-height: 40rpx;
   }
</style>
