<template>
  <md-editor v-model="text" :theme="theme" previewTheme="github" />
</template>

<script setup>
  import { ref } from 'vue';
  import MdEditor from 'md-editor-v3';
  import 'md-editor-v3/lib/style.css';
  const text = ref('# ces');
  const theme = ref('light');
</script>
