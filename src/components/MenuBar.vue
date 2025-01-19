<template>
	<div class="h-16 text-white flex menu-bar justify-end">
		<div class="menu-bar-branding content-center mr-auto pl-16">
			Brand
		</div>
		<div class="menu-bar-item">
			Le Item 1
		</div>
		<div class="menu-bar-item">
			Le Item 2
		</div>
		<div class="menu-bar-item">
			<airplay-icon size="25" class="custom-class"></airplay-icon>
		</div>
		<div class="menu-bar-item">
			<button class="bg-red-800 hover:bg-red-400 text-white p-2 rounded-lg">Le Button</button>
		</div>
	</div>
</template>

<script>
import { AirplayIcon } from 'vue-feather-icons'
export default {
	components: {
		AirplayIcon
	}
}
</script>

<style>
</style>
