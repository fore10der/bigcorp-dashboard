<script setup>
import HierarchyList from "@/components/List/HierarchyList.vue";
import DashboardHeader from "@/components/DashboardHeader.vue";

const list = ["Saul Goodman", "Laus Badwoman", "Sual Badman"];
</script>

<template>
  <div class="w-full h-full flex flex-col">
    <div class="flex-none h-16">
      <DashboardHeader />
    </div>
    <div class="flex-auto flex">
      <div class="flex-none w-64 border-r">
        <HierarchyList :list="list" />
      </div>
      <div class="flex-auto bg-secondary"></div>
    </div>
  </div>
</template>

<style scoped></style>
