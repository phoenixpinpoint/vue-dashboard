<template>
	<div class="w-14 h-14 hover:w-1/6">
		<h1> Menu </h1>
		<SideNavItem item-icon="pi pi-th-large text-xl" item-label="Dashboard" />
	</div>
</template>

<script>
import 'primeicons/primeicons.css';
import SideNavItem from './SideNavItem'
export default {
	components:{
		SideNavItem 
	},
}
</script>

<style>
</style>
