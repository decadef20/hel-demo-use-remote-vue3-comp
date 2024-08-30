<template>
  <Alert message="加载远程 vite 组件"  />
</template>

<script lang="ts" setup>
import { defineAsyncComponent } from 'vue'
import { preFetchLib } from 'hel-micro'

const Alert = defineAsyncComponent(async () => {
  const mod = await preFetchLib('hel-tpl-remote-vue3-comps-vite')
  console.log('mod', mod)
  return mod.Alert
})
</script>
