<template>
    <div class="button-div">
        <button>{{message}}</button>
    </div>
</template>

<script>
export default {
    name: "Button",

    props: {
        message: String,
    }
}
</script>

<style scoped>
.button-div {
    margin: 20px;
}

.button-div button {
    padding: 15px;
    text-align: center;
    transition-duration: 0.3s;

    box-shadow: 4px 4px #999;
    border: none;
    border-radius: 10px;
    background-color: lightgreen;
    font-weight: bold;
}

.button-div button:hover{
    background-color: rgb(71, 231, 71);
}

.button-div button:active{
    box-shadow: 1px 1px #666;
    transform: translateY(4px);
}
</style>