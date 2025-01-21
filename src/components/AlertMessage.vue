<template>
  <div class="alert-message" :class="classObject">
    <div class="flex">
      <div :class="alertTypeIcon">
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
    ],
    computed: {
      classObject() {
        return {
          "bg-red-700": this.alertType === "error",
          "bg-green-700": this.alertType === "success",
          "bg-amber-700": this.alertType === "warning",
          "bg-cyan-700": !this.alertType
        }
      },
      alertTypeIcon() {
        return {
          "pi pi-times-circle text-xl": this.alertType === "error",
          "pi pi-check-circle text-xl": this.alertType === "success",
          "pi pi-exclamation-circle text-xl": this.alertType === "warning",
          "pi pi-info-circle text-xl": !this.alertType
        }
      }
    }

  }
</script>


<style>

</style>
