<template>
	<div class="h-screen w-screen bg-slate-900">
		<MenuBar />
		<div class="flex flex-wrap justify-center content-center text-center">
			<SideGutter />
			<h1 class="text-white w-2/3">App</h1>
			<SideGutter />
		</div>
	</div>
</template>
<script>
import MenuBar from './components/MenuBar.vue'
import SideGutter from './components/SideGutter.vue'

export default {
  name: 'App',
  components: {
	MenuBar,
	SideGutter
  }
}
</script>

<style>

</style>
