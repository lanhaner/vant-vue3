<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<van-button type="primary" url="/vant/mobile.html">URL 跳转</van-button>
		<van-button type="danger">危险按钮</van-button>
	</div>
</template>

<script>
	import {
		Button
	} from 'vant'

	export default {
		name: 'Home',
		components: {
			[Button.name]: Button //有赞引用Button组件库的特有方式
		}
	}
</script>
