<template>
    <div class="message-box">
        This is a message box
    </div>
</template>

<script>
export default {
    name: 'MessageBox',
}
</script>

<style scoped>
.message-box{
    /* GRID <row-start> / <column-start> / <row-end> / <column-end> */
    grid-area: 1 / 1 / 3 / 5;

    background-color: yellow;
}
</style>