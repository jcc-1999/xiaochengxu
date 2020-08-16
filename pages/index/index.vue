<template>
	<view>
		<!-- <text>{{title}}</text> -->
		<view class="aa">
			<input class="aa_1" type="text" placeholder="搜索"/>
		</view>
		<view class="uni-padding-wrap">
			<view class="page-section swiper">
				<view class="page-section-spacing">
					<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
						<swiper-item>
							<view class="swiper-item">
								<image style="width: 100%;" src="../../static/images/shouye1.jpg"></image>
							</view>
						</swiper-item>
						<swiper-item>
							<view class="swiper-item">
								<image style="width: 100%;" src="../../static/images/shouye2.jpg"></image>
							</view>
						</swiper-item>
						<swiper-item>
							<view class="swiper-item">
								<image style="width: 100%;" src="../../static/images/shouye3.jpg"></image>
							</view>
						</swiper-item>
					</swiper>
				</view>
			</view>
		</view>
		<scroll-view class="bb" scroll-x="true">
			<view class="bb_1">
				<view class="iconfont icon-groupctrl" style="font-size: 50upx;"></view>
				<view>歌手</view>
			</view>
			<view class="bb_1">
				<view class="iconfont icon-instruction" style="font-size: 50upx;"></view>
				<view>排行</view>
			</view>
			<view class="bb_1">
				<view class="iconfont icon-menu" style="font-size: 50upx;"></view>
				<view>分类歌单</view>
			</view>
			<view class="bb_1">
				<view class="iconfont icon-audio" style="font-size: 50upx;"></view>
				<view>电台</view>
			</view>
			<view class="bb_1">
				<view class="iconfont icon-watchseries" style="font-size: 50upx;"></view>
				<view>视频</view>
			</view>
		</scroll-view>
		<view class="cc clear">
			<view class="cc_1 left">
				<image src="../../static/images/sanjiao.png" mode="aspectFit"></image>
			</view>
			<view class="right">
				<view class="cc_2">
					<view style="width: 350upx;">
						<view>新歌新碟</view>
						<view style="font-size: 30upx;">神秘嘉宾先生选择新歌</view>	
					</view>
					<image src="../../static/images/301.jpg" mode="aspectFit"></image>
				</view>
				<view class="cc_2">
					<view style="width: 350upx;">
						<view>动画片专辑|热映</view>
						<view style="font-size: 30upx;">李健老狼联手现场</view>	
					</view>
					<image src="../../static/images/302.jpg" mode="aspectFit"></image>
				</view>
			</view>
		</view>
		<view>
			<view style="text-align: center;">为你推荐</view>
		</view>
		<view class="dd">
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (1).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>你是否读过我写的信</view>
					<view style="font-size: 30upx;color: #b8b2b1;">The Popest</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (2).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>师傅说</view>
					<view style="font-size: 30upx;color: #b8b2b1;">徐梦宸</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (3).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>青史无他</view>
					<view style="font-size: 30upx;color: #b8b2b1;">河图</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (4).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>姐姐真漂亮</view>
					<view style="font-size: 30upx;color: #b8b2b1;">时代少年团</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (5).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>安排</view>
					<view style="font-size: 30upx;color: #b8b2b1;">RiCH BOOM</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (6).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>陪着你</view>
					<view style="font-size: 30upx;color: #b8b2b1;">宋佳</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (7).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>还能做什么？</view>
					<view style="font-size: 30upx;color: #b8b2b1;">王琪玮</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (8).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>Pinky Murder</view>
					<view style="font-size: 30upx;color: #b8b2b1;">Lil Ghost小鬼</view>	
				</view>
			</view>
			<view class="cc_2" style="margin-left: 10px;margin-top: 5px;">
				<image src="../../static/images/yinyue (9).jpg" mode="aspectFit"></image>
				<view style="width: 350upx;margin-left: 10px;">
					<view>只道是寻常</view>
					<view style="font-size: 30upx;color: #b8b2b1;">小根号</view>	
				</view>
			</view>
		</view>
		
		
		
		
		
		
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				indicatorDots: true,
				autoplay: true,
				interval: 2000,
				duration: 500
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.clear:after{
	    content: "";
	    display: block;
	    clear: both;
	}
	.left{
	    float: left;
	}
	.right{
	    float: right;
	}
	.aa{
		display:flex;
		height: 100upx;
		background-color: #f55500;
	}
	.aa_1{
		width: 90%;
		text-align: center;
		border: 1px solid #f0f0f0;
		border-radius: 10upx;
		margin-top: 20upx;
		margin-left: 20upx;
		background-color: #ffffff;
	}
	.bb{
		width: 100%;
		margin: 0 auto;
		background-color: #f55500;
		display: flex;
		flex-wrap: nowrap;
		white-space: nowrap;
	}
	.bb .bb_1{
		width: 30%;
		margin: 20upx 10upx;
		text-align: center;
		color: #ffffff;
		display: inline-block;
	}
	.cc{
		padding: 10px 10px;
	}
	.cc_1{
		width: 30%;
		height: 220upx;
		line-height: 320upx;
		color: #ffffff;
		text-align: center;
		background: url(../../static/images/300.jpg) no-repeat;
		background-size:cover;
		box-shadow:0px 0px 5px 5px #dfdfdf;
	}
	.cc_1 image{
		width: 100upx;
		height: 100upx;
	}
	.cc_2{
		width: 100%;
		display: flex;
		background-color: #f3f1f1;
		margin-bottom: 20upx;
	}
	.cc_2 image{
		width: 100upx;
		height: 100upx;
	}
	.dd_1{
		margin-left: 10px;
		display: inline-block;
	}
	.dd_1 image{
		width: 15%;
		height: 48px;
	}
</style>
