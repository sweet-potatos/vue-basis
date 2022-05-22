<template>
	<div>
		<School></School>
		<Student></Student>
	</div>
</template>

<script>
	import School from './School.vue';
	import Student from './Student.vue';
	
	const App = {
		name: 'App',
		components: {
			School,
			Student
		}
	}
</script>