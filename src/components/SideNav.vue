<template>
	<div class="bg-white m-4 border-solid border-1 rounded-lg shadow-lg shadow-slate-400 justify-center text-center">
		<h1 class="py-2"> <b>Menu</b> </h1>
		<SideNavItem item-icon="pi pi-th-large text-xl" item-label="Dashboard"/>
    <SideNavItem item-icon="pi pi-briefcase text-xl" item-label="Cases"/>
    <SideNavItem item-icon="pi pi-calendar text-xl" item-label="Calendar"/>
    <SideNavItem item-icon="pi pi-users text-xl" item-label="Clients"/>
    <SideNavItem item-icon="pi pi-folder" item-label="Fillings"/>
    <SideNavItem item-icon="pi pi-dollar text-xl" item-label="Billables"/>
    <SideNavItem item-icon="pi pi-id-card text-xl" item-label="Personnel"/>
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
