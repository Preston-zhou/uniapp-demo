<template>
	<view>
		<button @click="handleClick(20, $event)" type="primary">button</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				showText: true
			}
		},
		methods: {
			handleClick(num,e){
				console.log('aaa',num, e)
			}
		}
	}
</script>

<style>
@import url("./a.css");
.box{
	width:100px;
	height: 100px;
	background:#007AFF;
}
.box-active{
	background-color: #DD524D;
}
.iconfont {
	font-size: 50px;
}
</style>
