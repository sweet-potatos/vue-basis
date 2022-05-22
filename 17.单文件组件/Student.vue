<template>
	<!-- 组件结构 html -->
	<div>
		<h2>{{name}}</h2>
		<h2>{{age}}</h2>
	</div>
</template>

<script>
	// 组件交互相关的代码(数据、方法等)
	const Student = {
		name: 'Student',
		data(){
			return {
				name: '张三',
				age: 18,
			}
		},
	}
	
	export default Student;
</script>

<style>
	/* 组件的样式 */
</style>