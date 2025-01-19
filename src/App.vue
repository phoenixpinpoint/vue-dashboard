<template>
	<div class="h-screen w-screen flex flex-col">
		<MenuBar />
		<div class="flex grow bg-slate-200">
			<SideNav />
			<h1 class="text-white grow">App</h1>
		</div>
	</div>
</template>
<script>
import MenuBar from './components/MenuBar.vue'
import SideNav from './components/SideNav.vue'

export default {
  name: 'App',
  components: {
	MenuBar,
	SideNav
  }
}
</script>

<style>

</style>
