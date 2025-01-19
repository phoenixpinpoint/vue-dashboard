<template>
	<div class="bg-white m-4 border-solid border-1 rounded-lg shadow-lg shadow-slate-400 justify-center text-center">
		<h1> <b>Menu</b> </h1>
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
