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
    
<style lang="scss">
@import '../style/common.scss';
@import '../style/variables.scss';



</style>
