<template>
  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>

<script setup>
const enableCustomLayout = () => {
  setPageLayout("default");
};
definePageMeta({
  layout: false,
});
</script>
