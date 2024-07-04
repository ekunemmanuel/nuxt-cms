<template>
  <div>
    <QuillEditor theme="snow" toolbar="full" v-model:content="content"/>
    {{content}}
  </div>
</template>

<script lang="ts" setup>

const content = ref()

</script>

<style></style>
