<template>
	<view>
		<view>
			<view class="details_box">
				<h1 class="box_title">节能减排研究成果</h1>
				<p class="box_company"><span>单位名称:</span>山西省科技局</p>
				<p class="box_company"><span>合作方式:</span>山西省太原市迎泽区府西街128号</p></p>
				<p class="box_company"><span>联系方式:</span>153 6839 1683</p>
			</view>
			</view>
			<!-- 项目介绍 -->
			<view class="project">
				<h1 class="project_title">项目介绍</h1>
				<p class="project_content">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划》</p>
					<p class="project_content">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划》</p>
					<p class="technical">山西省科学技术厅</p>
					<p class="time">2018-10-24</p>
			</view>
			<view class="project">
				<h1 class="project_title">知识产权情况</h1>
				<p class="project_content">为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划》</p>
					<p class="technical">山西省科学技术厅</p>
					<p class="time">2018-10-24</p>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
	.details_box{
		width: 704rpx;
		height: 391rpx;
		border-radius: 10rpx;
		 box-shadow:0 -1px 10px rgba(0,0,0,0.1);
		 margin: 0 auto;
		 margin-top: 41rpx;
	}
	
	
	.box_title{
	font-size: 44rpx;
	font-weight: 400;
	padding-top: 61rpx;
	padding-left: 56rpx;
	line-height: 100rpx;
	}
	.box_company{
		height: 66rpx;
		line-height: 66rpx;
		font-size: 28rpx;
		padding-left: 75rpx;
		position: relative;
	}
	.box_company span{
		color:#a5a7af;
	}
	.box_company::before{
		width: 13rpx;
		height: 5rpx;
		content: "";
		 background-color: #fdab3e;
		 position: absolute;
		 left: 48rpx;
		top: 30rpx;
	}
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
	.technical{
		font-size: 24rpx;
		text-align: right;
	}
	.time{
		font-size: 26rpx;
		text-align: right;
		color: #cdcdcf;
	}
</style>
