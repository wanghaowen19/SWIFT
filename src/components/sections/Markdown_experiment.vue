<script setup>
import page from '../mds/experiment.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12" class="mdx-content">
            <page />
        </el-col>
    </el-row>

  </div>
</template>