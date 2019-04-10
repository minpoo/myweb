<template>
	<view class="content">
        <image class="logo" src="/static/logo.png"></image>
		<view>
            <text class="title">{{title}}</text>
			<a href="http://www.cxcuu.com">欢迎</a>
        </view>
	</view>
</template>

<script>
	//window.location.href="http://www.cxcuu.com"
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {
            // window.location.href="http://www.cxcuu.com"
		},
		methods: {
               
		}
	}
	
</script>

<style>
	.content {
		text-align: center;
		height: 400upx;
	}
    .logo{
        height: 200upx;
        width: 200upx;
        margin-top: 200upx;
    }
	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
