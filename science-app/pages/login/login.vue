<template>
	<view>
		<view class="login_banner">
			<image src="../../static/login/loginbanner.png" mode=""></image>
			<view class="login_picture">
				<image src="@/static/login/headPortrait.png" mode=""></image>
			</view>
		</view>
		
		<form class="login_form" @submit="" @reset="">
			<input class="name login_input" type="text" placeholder="请输入完整的企业名称" />
			<input class="password login_input" type="text" placeholder="请输入密码" />
			<button class="btn" type="default">登录</button>
		</form>
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
	.login_banner{
		position: relative;
	}
	.login_banner image{
		height: 505rpx;
		width: 100%;
		background-repeat: no-repeat;
		background-position: center;
	}
	.login_picture{
		width: 182rpx;
		height: 182rpx;
		border-radius: 50%;
		background: #384068;
		position: absolute;
		left: 50%;
		bottom: 0;
		margin-left: -91rpx;
		margin-bottom: -91rpx;
	}
	.login_picture image{
		width: 166rpx;
		height: 166rpx;
		border-radius: 50%;
		background: #fff;
		position: absolute;
		left: 0;
		top: 0;
		right: 0;
		bottom: 0;
		margin: auto;
	}
	.login_form{
		display: block;
		width: 700rpx;
		height: auto;
		overflow: hidden;
		margin: 0 auto;
		margin-top: 170rpx;
	}
	.login_input{
		display: block;
		margin: 0 auto;
		margin-top: 5px;
		width: 690rpx;
		height: 90rpx;
		box-shadow: 0rpx 0rpx 5rpx #384068;
		color: #9c9fb3;
		padding-left: 123rpx;
		box-sizing: border-box;
		font-size: 24rpx;
		border-radius: 8rpx;
	}
	.login_form .name{
		position: relative;
	}
	.login_form .name::after{
		content: "";
		position: absolute;
		left: 47rpx;
		top: 27rpx;
		background: url(@/static/login/name.png)no-repeat center/100% 100%;
		width: 32rpx;
		height: 36rpx;
	}
	.login_form .password{
		margin-top: 20rpx;
		position: relative;
	}
	.login_form .password::after{
		content: "";
		position: absolute;
		left: 45rpx;
		top: 24rpx;
		background: url(@/static/login/password.png) no-repeat center/100% 100% ;
		width: 35rpx;
		height: 43rpx;
	}
	.login_form .btn{
		margin-top: 110rpx;
		background: #384068;
		color: #fff;
		border-radius: 6px;
		border: 0px;
		font-size: 30rpx;
		height: 90rpx;
	}
</style>
