<template>
	<!-- 组件结构 html -->
	<div>
		<h2>{{name}}</h2>
		<h2>{{address}}</h2>
	</div>
</template>

<script>
	// 组件交互相关的代码(数据、方法等)
	const School = {
		//组件定义时，一定不要写el配置项，因为最终所有的组件都要被一个vm接管，由vm决定服务于哪个容器
		name: 'School',
		data(){
			return {
				name: '中大',
				address: '广州',
			}
		},
	}
	
	export default School;
</script>

<style>
	/* 组件的样式 */
</style>