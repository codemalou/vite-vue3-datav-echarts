<script setup>
import {ref,reactive} from 'vue'
const config = ref({
    header: ['时间', '信息', '数标'],
    data: [
        ['2024-1-1', '松散', '2.x.'],
        ['行2列1', '行2列2', '行2列3'],
        ['行3列1', '行3列2', '行3列3'],
        ['行4列1', '行4列2', '行4列3'],
        ['行5列1', '行5列2', '行5列3'],
        ['行6列1', '行6列2', '行6列3'],
        ['行7列1', '行7列2', '行7列3'],
        ['行8列1', '行8列2', '行8列3'],
        ['行9列1', '行9列2', '行9列3'],
        ['行10列1', '行10列2', '行10列3'],
    ],
    index: true,
    columnWidth: [50],
    align: ['center'],
    })
</script>

<template>
<dv-scroll-board :config="config" style="width:100%;height:300px"/>
</template>

<style scoped>

</style>
