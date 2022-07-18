<template>
    <main>
        <div class="cards-container container-fluid">
            <div v-for="(novel,index) in novelCards" :key="index" class="single-cards">
                
            </div>
        </div>
    </main>
</template>

<script>

export default {
   

    name: 'DcMain',
    

}


</script>

<style lang="scss" scoped>
@import '../style/common.scss';
@import '../style/variables.scss';

.cards-container {
    background-color: $brand_secondary_color;
    width: 100%;
    height: 20vh;
    color: white;
    text-align: center;
    font-size: 40px;
}
</style>
