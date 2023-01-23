<script>
export default {
    props: {
        comic: Object,
    }
}
</script>

<template>
    <div class="card">
        <div class="carde-image">
            <img :src="series.thumb" alt="">
        </div>
        <div class="card-title">
            {{ comic.series }}
        </div>
    </div>
</template>
<style scoped lang="scss">

</style>