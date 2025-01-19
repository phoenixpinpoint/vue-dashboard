<template>
	<div class="bg-red-800 h-full w-full flex content-center" @mouseover="expanded = true" @mouseleave="expanded = false">
    <i :class=itemIcon></i>
    <div v-show="expanded">{{itemLabel}}</div>
	</div>
</template>

<script>
export default {
  data() {
    return {expanded: false}
  },
  props : [
    'itemIcon',
    'itemLabel'
  ]
}
</script>

<style>
</style>

