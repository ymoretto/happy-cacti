<template>
    <div class="navbar">
            <div>Happy Cacti Game</div>
            <img src="@/assets/cacto-nav.svg" alt="">
            <div>Day: {{daysTime}} / 20</div>
            <img src="@/assets/cacto-nav.svg" alt="">
            <div>Plants: {{plants}} / 12 </div>
            <img src="@/assets/cacto-nav.svg" alt="">
            <div>Restart Btn</div>
    </div>
</template>

<script>
export default {
    name: 'Navbar',

    data: () => ({
        daysTime: 1,
        plants: 1,
    })
}
</script>

<style scoped>
.navbar {
    background-color: lightgreen;
    height: 40px;
    padding: 10px 50px;
    text-align: center;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

img {
    max-height: 15px;
}
</style>