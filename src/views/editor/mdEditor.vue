<template>
  <div class="page-container">
    <Descrition title="Markdown">
      <template #descrition>
        Vue3-admin 推荐使用
        <a href="https://github.com/imzbf/md-editor-v3" target="_blank">md-editor-v3</a>
        作为markdown编辑器
      </template>
    </Descrition>
    <div class="edit-content">
      <Descrition title="演示" :showDesc="false"></Descrition>
      <MdEditor />
    </div>
  </div>
</template>

<script setup>
  import Descrition from '@/components/Descrition/index.vue';
  import MdEditor from '@/components/MdEditor/index.vue';
</script>

<style lang="scss" scoped></style>
