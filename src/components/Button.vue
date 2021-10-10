<template>
    <div class="button">
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

</style>