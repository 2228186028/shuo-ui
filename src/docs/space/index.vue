<template>
  <div>
    <div class="doc__title">Space 间距</div>
    <div class="doc__desc">设置组件之间的间距</div>
    <demo :code="Demo1_Code" title="基础用法">
      <demo1 />
    </demo>
    <demo :code="Demo2_Code" title="垂直间距">
      <demo2 />
    </demo>
  </div>
</template>

<script setup lang="ts">
import { Demo1, Demo1_Code, Demo2, Demo2_Code } from './demo'
</script>
