<template>
    <div class="actions-menu">
        those are the actions from the menu
    </div>
</template>

<script>
export default {
    name: 'ActionsMenu',
}
</script>

<style scoped>
.actions-menu {
    /* GRID <row-start> / <column-start> / <row-end> / <column-end> */
    grid-area: 1 / 5 / 7 / 7;

    background-color: gray;
}
</style>