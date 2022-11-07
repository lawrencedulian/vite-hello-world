<script>
export default {
    data() {
        return {
            image: "https://picsum.photos/seed/picsum/400/400"
        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <img :src="image" alt="">
    </div>
</template>

<style scoped>
.jumbotron {
    width: 100%;
    height: 400px;
}

.jumbotron img {
    width: 100%;
    height: 100%;

    object-fit: cover;
}
</style>