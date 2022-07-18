<template>
    <main>
        <div class="jumbotron">
            <div class="jumbotron-content">
                contents goes here
            </div>
        </div>
    </main>
</template>

<script>

export default {
    name: 'DcMain',
    data() {
        return {
            
        }
    }

}


</script>

<style lang="scss" scoped>
@import '../style/common.scss';
@import '../style/variables.scss';

.jumbotron {
    background-color: $brand_secondary_color;
    width: 100%;
    height: 20vh;
    color: white;
    text-align: center;
    font-size: 40px;
}

</style>
