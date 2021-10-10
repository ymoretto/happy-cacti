<template>
    <div class="actions-menu">
        <div class="btn-wrapper">
            <Button 
                message="Water"
            />
            <Button 
                message="Open the window"
            />
            <Button 
                message="Talk with the plants"
            />
            <Button 
                message="Next day"
            />
        </div>
    </div>
</template>

<script>
import Button from './Button'

export default {
    name: 'ActionsMenu',

    components: {
        Button,
    }
}
</script>

<style scoped>
.actions-menu {
    /* GRID <row-start> / <column-start> / <row-end> / <column-end> */
    grid-area: 1 / 5 / 7 / 7;

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.btn-wrapper{
    background-color: gray;
}
</style>