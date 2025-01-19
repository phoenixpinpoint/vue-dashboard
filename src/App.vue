<template>
	<div class="h-screen w-screen flex flex-col">
		<MenuBar />
		<div class="flex grow bg-slate-200">
			<SideNav />
      <div class="mr-4 my-4">
        <DataCard />
      </div>
		</div>
	</div>
</template>
<script>
import MenuBar from './components/MenuBar.vue'
import SideNav from './components/SideNav.vue'
import DataCard from './components/DataCard.vue'

export default {
  name: 'App',
  components: {
    MenuBar,
    SideNav,
    DataCard
  }
}
</script>

<style>

</style>
