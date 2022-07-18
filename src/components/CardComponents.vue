<template>
    <div>
        <div>
            <img class="w-100" :src="singleSlide.thumb" :alt="singleSlide.type">
        </div>
        <h3>{{ singleSlide.series }}</h3>
    </div>
</template>

<script>

export default {
    props: [
        "singleSlide"
    ]
}


</script>
    
<style lang="scss" scoped>
@import '../style/common.scss';
@import '../style/variables.scss';

h3{
    font-size: 15px;
    font-weight: 200;
    text-transform: uppercase;
    margin: 10px 0;
}
img{
    height: 180px;
    object-fit: cover;
    object-position: top;
}

</style>
