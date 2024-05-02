<script setup>
// ? https://medium.com/@chiyang1118/%E5%82%99%E4%BB%BD-ui%E5%B0%8F%E7%AD%86%E8%A8%98-html5-drag-and-drop-%E5%8A%9F%E8%83%BD%E5%AF%A6%E4%BD%9C-f26494e99fca
</script>

<template>
    <button draggable="true">&</button>
</template>

<style scoped>
/* To prevent user selecting inside the drag source */
[draggable="true"] {
    user-select: none;
    -moz-user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
}
</style>