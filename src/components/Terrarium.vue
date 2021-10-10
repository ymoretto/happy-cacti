<template>
    <div class="terrarium">
        this is a terrarium
    </div>
</template>

<script>
export default {
    name: 'Terrarium',
}
</script>

<style scoped>
.terrarium {
    /* GRID <row-start> / <column-start> / <row-end> / <column-end> */
    grid-area: 3 / 1 / 7 / 5;

    background-color: rgb(250, 124, 124);
}
    
</style>