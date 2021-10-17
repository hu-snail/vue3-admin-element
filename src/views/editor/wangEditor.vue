<template>
  <div class="page-container">
    <Descrition title="富文本 WangEditor">
      <template #descrition>
        Vue3-admin 推荐使用
        <a href="https://www.wangeditor.com/" target="_blank">WangEditor</a>
        作为富文本编辑器
      </template>
    </Descrition>
    <div class="edit-content">
      <Descrition title="演示" :showDesc="false"></Descrition>
      <WandEditor />
    </div>
  </div>
</template>

<script setup>
  import Descrition from '@/components/Descrition/index.vue';
  import WandEditor from '@/components/WandEditor/index.vue';
</script>

<style lang="scss" scoped></style>
