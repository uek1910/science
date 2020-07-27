<template>
	<view>
		<view class="card">
			<h2 class="title">{{title}}</h2>
			<button class="card_btn">相关资料</button>
			<view class="card-con">
				<p><i></i><span class="fixed">单位名称：</span><span>{{name}}</span></p>
				<p><i></i><span class="fixed">合作方式：</span><span>{{method}}</span></p>
				<p><i></i><span class="fixed">联系方式：</span><span>{{phone}}</span></p>
			</view>
		</view>
		<view class="res">
			<view class="produce art">
				<p class="con-title">项目介绍</p>
				<p class="content">{{indroduce}}</p>
				<view class="inscribe">
					<p class="name">{{indroduceIssue}}</p>
					<p class="date">{{indroduceDate}}</p>
				</view>
			</view>
			<view class="art">
				<p class="con-title">知识产权情况</p>
				<p class="content">{{property}}</p>
				<view class="inscribe">
					<p class="name">{{propertyIssue}}</p>
					<p class="date">{{propertyDate}}</p>
				</view>
			</view>
		</view>
	</view>
</template>
<script>
	export default {
		data() {
			return {
				title:'太阳能发电项目需求',
				name:'山西省科技局',
				method:'山西省太原市',
				phone:'11111111111',
				// content:[
				// 	    {
				// 		indroduce:'为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划 拷贝 3',
				// 		indroduceIssue:'山西省科学技术厅',
				// 		indroduceDate:'2018-10-24',
				// 		},
				// 		{
				// 		indroduce:'为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划 拷贝 3',
				// 		indroduceIssue:'山西省科学技术厅',
				// 		indroduceDate:'2018-10-24',
				// 		}
				// 	]
				indroduce:'为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划 拷贝 3',
			    indroduceIssue:'山西省科学技术厅',
				indroduceDate:'2018-10-24',
				property:'为贯彻落实省政府《山西省深化省级财政科技计划专项基金等管理改革方案》，规范项目管理专业机构，我们制定了《山西省省级财政科技计划 拷贝 3',
				propertyIssue:'山西省科学技术厅',
				propertyDate:'2018-10-24'
			}
		},
		methods: {
			
		},
		components:{
			
		}
	}
</script>

<style>
.card{
	width:702rpx;
	height:491rpx;
	margin:0 auto;
	margin-top:41rpx;
	box-shadow: 0rpx 0rpx 15rpx #ccc;
}
.title{
		font-size:42rpx;
		color:#4a4c57;
		padding-top:64rpx;
		margin-left:48rpx;
	}
.card_btn{
	width:124rpx;
	height:36rpx;
	background-color:#20c8bb;
	border-radius:18rpx;
	font-size:20rpx;
	color:#fff;
	text-align:center;
	line-height:36rpx;
	margin-left:48rpx;
	margin-top:21rpx;
}
.card .card-con{
	margin-left:48rpx;
	margin-top:95rpx;
	font-size:28rpx;
	font-weight:600;
	letter-spacing: 2rpx;
}
.card .card-con p{
	width:100%;
	height:62rpx;
}
.card .card-con i{
	display:block;
	width:12rpx;
	height:5rpx;
	background-color:#fdab3e;
	border-radius:6rpx;
	margin-top:18rpx;
	margin-right:14rpx;
	float:left;
}
.card .card-con .fixed{
	color:#a5a7af;
}
.card .card-con span{
	color:#4a4c57;
}
.res{
	width:615rpx;
	height:auto;
	overflow: hidden;
	margin:0 auto;
	margin-top:69rpx;
}
.produce{
	width:100%;
	height:auto;
	overflow: hidden;
	border-bottom:2px solid #f7f7f7;
	margin-bottom:60rpx;
}
.art .con-title{
	height:54rpx;
	font-size:26rpx;
	color:#a5a7af;
}
.art .inscribe{
	float:right;
	text-align:right;
	margin-top:97rpx;
	margin-bottom:57rpx;
}
.art .content,
.inscribe .name{
	font-size:24rpx;
	color:#565970;
	line-height:36rpx;
	letter-spacing: 1.5rpx;
}
.inscribe{
	font-size:20rpx;
	color:#a4a5ab;
}
</style>
