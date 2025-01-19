<template>
	<div class="bg-red-800 h-full w-full">
		<!--This is where you are in this problem getting the icon to passthrough-->
		<!--Honestly there is a vue bind method for HTML that should be used here.-->
		<!--Atleast that is what I think-->
		<!--Also I do know that this type of comment is a multiline, these comments were
			seperate at one point-->
		<i class={{itemIcon}}></i>
		{{itemLabel}}
	</div>
</template>

<script>
export default {
	props: [
		'itemId',
		'itemIcon',
		'itemLabel'
	]

}
</script>

<style>
</style>

