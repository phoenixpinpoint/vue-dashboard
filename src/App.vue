<template>
	<div class="h-screen w-screen flex flex-col">
		<MenuBar />
		<div class="flex grow bg-slate-200">
			<SideNav />
      <div class="flow">
        <AlertMessage alert-type="error" alert-message="Le Test"/>
        <div class="mr-4 my-4 space-x-4 flex">
          <DataCard />
          <DataCard />
          <DataCard />
          <DataCard />
        </div>
      </div>
		</div>
	</div>
</template>
<script>
import MenuBar from './components/MenuBar.vue'
import SideNav from './components/SideNav.vue'
import AlertMessage from './components/AlertMessage.vue'
import DataCard from './components/DataCard.vue'

export default {
  name: 'App',
  components: {
    MenuBar,
    SideNav,
    DataCard,
    AlertMessage
  }
}
</script>

<style>

</style>
