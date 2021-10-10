<template>
    <div class="canvas">
        <MessageBox />
        <Terrarium />
        <ActionsMenu />
    </div>
</template>

<script>
import MessageBox from './MessageBox'
import Terrarium from './Terrarium'
import ActionsMenu from './ActionsMenu'

export default {
    name: 'Canvas',

    components: {
        MessageBox,
        Terrarium,
        ActionsMenu,
    }
}
</script>

<style scoped>
.canvas{
    display: grid;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;

    height: calc(100vh - 70px);
    border: 10px ridge rgb(71, 33, 11);
}
</style>