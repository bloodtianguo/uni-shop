<template>
	<view>
		<button type="default" @click="navigateTo">支付</button>
	</view>
</template>
<script>
import PlatformService from "@/services/common/platformService.js";
export default {
	data() {
		return {};
	},
	methods: {
		navigateTo() {
			PlatformService.pushUrl("/pages/order/payComplete");
		}
	}
};
</script>
