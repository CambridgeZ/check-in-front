<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view>
			<text class="title">{{title}}</text>
		</view>
	</view>
	
</template>

<script>
	import {uniBadge} from '@dcloudio/uni-ui'

	export default {
		name: 'index',
		data() {
			return {
				title: '欢迎使用!'
			}
		},
		comments: {
			uniBadge
		},
		mounted(){
			setTimeout(()=>{
				uni.navigateTo({
					url: '/pages/register/index'
				})
			}, 5000)	
		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin: 200rpx auto 50rpx auto;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
