<template>
  <div class="w-full h-full flex flex-col">
    <div class="flex-none h-16">
      <Header/>
    </div>
    <div class="flex-auto flex">
      <div class="flex-none w-64 border-r">
        side menu
      </div>
      <div class="flex-auto bg-secondary">

      </div>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  name: "Layout",
  components: {Header}
}
</script>

<style scoped>

</style>