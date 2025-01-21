<template>
  <div class="alert-message bg-red-700">
    <div class="flex">
      <div v-if="alertType === 'error'" class="pi pi-times-circle text-xl">
      </div>
      <div class="ml-4">
        {{alertMessage}}
      </div>
      <div class="pi pi-times text-xl last:ml-auto hover:cursor-pointer">
      </div>
    </div>
  </div>
</template>



<script>
  export default {
    props: [
      'alertType',
      'alertMessage'
    ]
  }
</script>


<style>

</style>
