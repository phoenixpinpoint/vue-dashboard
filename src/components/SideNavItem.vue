<template>
	<div class="flex flex-row content-center mx-4 my-2 px-4 py-2 space-x-4 hover:bg-slate-900 hover:cursor-pointer hover:text-white hover:border-solid hover:rounded-xl">
    <i :class=itemIcon></i>
    <div>{{itemLabel}}</div>
	</div>
</template>

<script>
export default {
  data() {

  },
  props : [
    'itemIcon',
    'itemLabel'
  ]
}
</script>

<style>
</style>

