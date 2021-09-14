
<template>
	<view>
		<uni-list>
			<uni-list-item style="height:170rpx;" title="伊藤三叶" note="微信号:ye2587842047" showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/test.jpg" thumbSize="lg"></uni-list-item>
			<uni-list-item title="支付"   showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/static/wechatpay.png" thumbSize="base"/>
			<uni-list-item title="收藏" showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/static/like.png" thumbSize="base"/>
			<uni-list-item title="朋友圈" showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/static/pyq.png" thumbSize="base" />
			<uni-list-item title="卡包" showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/static/kb.png" thumbSize="base"/>
			<uni-list-item title="表情" showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/static/bq.png" thumbSize="base"></uni-list-item>
			<uni-list-item title="设置" showArrow thumb="https://itomitsuha.oss-cn-guangzhou.aliyuncs.com/static/setting.png" thumbSize="base"></uni-list-item>
		</uni-list>
	</view>
</template>
<script>
	export default {
		components: {},
		data() {
			return {};
		},
		methods: {
			onClick(e) {
				uni.showToast({
					title: '点击反馈'
				});
			}
		}
	};
</script>

