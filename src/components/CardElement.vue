<script>
export default {
    name: 'Card',
    props: {
        img: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <div><img :src="img"></div>
        <h3>{{ title }}</h3>
    </div>
</template>

<style lang="scss" scoped>

h3{
    color: white;
    font-size: 12px;
    padding-top: 10px;
}

</style>