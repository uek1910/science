<template>
	<view class="content">
		<view class="top">
			<view :class="['top_1',{active:state===1}]" @click="state=1">
				人员状况
			</view>
			<view :class="['top_1',{active:state===2}]" @click="state=2">
				营业执照
			</view>
			<view :class="['top_1',{active:state===3}]" @click="state=3">
				自由技术结果
			</view>
		</view>
		
		<view class="bottom">
			<view :class="['all',{actives:state ===1}]">
				 <view class="status">
					<view class="status_public left">
						<image src="@/static/compont/info_4.png" class="status_img"></image>
						<view class="status_text1">所有人员</view>
						<view class="status_text2"><span>268</span>人</view>
					</view>
					<view class="status_public right">
						<image src="@/static/compont/info_3.png" class="status_img"></image>
						<view class="status_text1">研发人员</view>
						<view class="status_text2"><span>64</span>人</view>
					</view>
				</view> 
				
				 <view class="personnel">
					<view class="personnel_list">
						<image src="@/static/compont/info_1.png"  class="personnel_img"></image>
						<view class="personnel_text1">苏婵</view>
						<view class="personnel_text2">研究生</view>
						<view class="personnel_text3">职称：高级技术员</view>
					</view>
					<view class="personnel_list">
						<image src="@/static/compont/info_1.png"  class="personnel_img"></image>
						<view class="personnel_text1">苏婵</view>
						<view class="personnel_text2">研究生</view>
						<view class="personnel_text3">职称：高级技术员</view>
					</view>
					<view class="personnel_list">
						<image src="@/static/compont/info_1.png"  class="personnel_img"></image>
						<view class="personnel_text1">苏婵</view>
						<view class="personnel_text2">研究生</view>
						<view class="personnel_text3">职称：高级技术员</view>
					</view> 
				</view>
			</view>
			<!-- 所有人员结束 -->
			
			
			<!-- 营业执照开始 -->
			<view :class="['license',{actives:state ===2}]">
				<view class="business">
					<image src="@/static/compont/info_5.png" mode=""></image>
				</view>
			</view>
			<!-- 营业执照结束 -->
			
			
			<!--自有技术成果开始  -->
			<view :class="['start',{actives:state ===3}]">
				<view class="results">
					<view class="results_list">
						<image src="@/static/compont/info_2.png" class="results_img1"></image>
						<view class="results_text1">自由研究成果一</view>
						<image src="@/static/compont/info_6.png" class="results_img2"></image>
						<view class="results_text2">研究成果的具体文字描述，最多20个字符</view>
					</view>
					<view class="results_list">
						<image src="@/static/compont/info_2.png" class="results_img1"></image>
						<view class="results_text1">自由研究成果一</view>
						<image src="@/static/compont/info_6.png" class="results_img2"></image>
						<view class="results_text2">研究成果的具体文字描述，最多20个字符</view>
					</view>
					<view class="results_list">
						<image src="@/static/compont/info_2.png" class="results_img1"></image>
						<view class="results_text1">自由研究成果一</view>
						<image src="@/static/compont/info_6.png" class="results_img2"></image>
						<view class="results_text2">研究成果的具体文字描述，最多20个字符</view>
					</view>
				</view>
				
			</view>
			<!-- 自由技术成果结束 -->
		</view>
		<!-- 所有人员开始 -->
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				 state:1
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.content{
		width:100% ;
		height:100% ;
	}
	.top{
		width:725rpx ;
		height:45rpx ;
		padding-left:25rpx ;
		padding-top:23rpx ;
		overflow: hidden;
		background-color:#2c304c ;
		font-size:23rpx ;
		
	}
	.top_1{
		color:#7e808f;
		float: left;
		margin-right:64rpx ;
	}
	.active{
		color:#ffffff;
		position: relative;
	}
	.active::after{
		content: '';
		width:34rpx ;
		height:4rpx ;
		position: absolute;
		top:40rpx;
		left:34%;
		background-color:#fdab3e ;	
	}
	.bottom{
		width:100% ;
		height:1130rpx ;
	}
	/* 所有人开始 */
	.all{
		width:100% ;
		height:1130rpx ;
		display:none ;
	}
	.status{
		width:701rpx ;
		height:159rpx ;
		margin:37rpx auto ;
		
	}
	.status_public{
		width:333rpx ;
		height:159rpx ;
		border-radius:8rpx ;
		
	}
	.left{
		float: left;
		background-color:#20c8bb ;
	}
	.right{
		float: right;
		background-color:#fdab3e ;
	}
	.status_img{
		width:55rpx ;
		height:55rpx ;
		float: left;
		margin:22rpx 250rpx 25rpx 24rpx ;
	}	
	.status_text1{
		width:189rpx ;
		height:67rpx ;
		float: left;
		font-size:28rpx ;
		color:#fff;
		margin-left:19rpx ;
	}
	
	.status_text2{
		width:125rpx ;
		height:67rpx ;
		float: left;
		font-size:28rpx ;
		color:#fff;
	}
	.status_text2 span{
		font-weight:700 ;
		padding-right:10rpx ;
	}
	.personnel{
		width:701rpx ;
		height:auto ;
		margin:24rpx auto ;
		overflow: hidden;
	}
	.personnel_list{
		width:100% ;
		height:150rpx ;
		border-bottom:2px solid #f7f7f7;
	}
	.personnel_list:last-child{
		border:none ;
	}
	.personnel_img{
		width:116rpx ;
		height:116rpx ;
		border-radius:50% ;
		margin-top:18rpx ;
		margin-right:29rpx ;
		float: left;
	}
	.personnel_text1{
		float: left;
		margin-top:50rpx ;
		font-size:28rpx ;
		width:455rpx ;
		height:40rpx ;
		color:#4a4c57;	
	}
	.personnel_text2{
		float: right;
		width: 96rpx;
		height: 40rpx;
		background-color:#e8f9f8 ;
		font-size:20rpx ;
		text-align: center;
		line-height:40rpx ;
		color:#52d4ca;
		margin-top:50rpx ;
		border-radius:20rpx ;
	}
	.personnel_text3{
		float: left;
		font-size:23rpx ;
		color:#8e8f99;
	}
	/* 所有人结束 */
	
	/* 营业执照开始 */
	.license{
		width:100% ;
		height:1130rpx;
		display: none;
	}
	.business{
		width:602rpx ;
		height:875rpx ;
		margin:83rpx auto ;
	}
	.business image{
		width:100% ;
		height:100% ;
	}
	/* 营业执照结束 */
	
	/* 自有技术成果开始 */
	.start{
		width:100% ;
		height:1130rpx;
		display:none ;
	}
	.results{
		width:660rpx ;
		height:auto ;
		overflow: hidden;
		margin:19rpx auto ;
	}
	.results_list{
		width:100% ;
		height:167rpx ;
		border-bottom:2px solid #f7f7f7;
	}
	.results_list:last-child{
		border:none ;
	}
	.results_img1{
		width:109rpx ;
		height:109rpx ;
		float: left;
		margin:29rpx 29rpx 29rpx 0rpx ;
	}
	.results_text1{
		width:516rpx ;
		height:46rpx ;
		float: left;
		margin-top:48rpx ;
		font-size:27rpx ;
		color:#4a4c57;
	}
	.results_text2{
		width:516rpx ;
		height:46rpx ;
		float: left;
		font-size:27rpx ;
		color:#8e8f99;
	}
	.results_img2{
		width:9rpx ;
		height:13rpx ;
		float: right;
		margin-top:54rpx ;
	}
	/* 自有技术成果结束 */
	.actives{
		display: block;
	}
</style>
