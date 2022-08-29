<script setup lang="ts">
import ListContainer from "@/components/List/ListContainer.vue";
import ListItem from "@/components/List/ListItem.vue";

interface HierarchyListProps {
  list: string[];
}

const props = defineProps<HierarchyListProps>();
</script>

<template>
  <ListContainer>
    <ListItem v-for="(item, index) in props.list" :key="index">{{
      item
    }}</ListItem>
  </ListContainer>
</template>

<style scoped></style>
