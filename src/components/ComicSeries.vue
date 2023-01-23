<script>
export default {
    props: {
        comic: Object,
    }
};
</script>

<template>
    <div class="card-image">
        <img :src="comic.thumb" :alt="comic.series">
        <h3>{{ comic.series }}</h3>
    </div>
</template>
<style scoped lang="scss">
.card-image {
    width: calc(100% / 6 - 2rem);
    margin: .5rem 1rem;

    img {
        width: 150px;
        height: 150px;
        object-fit: fill;
    }

    h3 {
        color: white;
        text-align: left;
        font-size: 15px;
        font-weight: 500;

    }
}
</style>