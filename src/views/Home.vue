<template>
	<div class="home">
		这是首页
		<Tabbar></Tabbar>
	</div>
</template>



<script>
	import Tabbar from '../components/commo/Tabbar.vue'
	export default {
		name: "home",
		components: {
			Tabbar
		}
	}
</script>