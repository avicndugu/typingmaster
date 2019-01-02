<template>
	<div class="test">
		<h1>{{title}}</h1>
		<h2>{{user.firstName}}</h2>
		<h2 v-text="user.lastName"></h2>
	</div>
</template>

<script>
	export default {
		name: 'test',
		data () {
			return {
				title:'Hello World',
				user:{
					firstName:'Janet',
					lastName:'Kega'
				}
			}
		}
	}
</script>

<style scoped>

/style>