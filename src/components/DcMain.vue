<template>
    <main>
        <section class="jumbotron">
            <div class="jumbotron-content">
                contents goes here
            </div>
        </section>

        <section class="product-container">
            <div id="wrapper">
                <div v-for="(product, index) in products" :key="index" class="product">
                    <div class="img-container">
                        <img :src="require(`../assets/img/${product.imgUrl}`)" :alt="product.text">
                        <h3>
                            {{ product.text }}
                        </h3>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<script>
export default {
    name: 'DcMain',
    data() {
        return {
            products: [
                {
                    text: 'Digital Comics',
                    imgUrl: 'buy-comics-digital-comics.png'
                },
                {
                    text: 'DC Merchandise',
                    imgUrl: 'buy-comics-merchandise.png'
                },
                {
                    text: 'Subscription',
                    imgUrl: 'buy-comics-subscriptions.png'
                },
                {
                    text: 'Shop Locatin',
                    imgUrl: 'buy-comics-shop-locator.png'
                },
                {
                    text: 'Dc Power Visa',
                    imgUrl: 'buy-dc-power-visa.svg'
                },
            ]
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

section.product-container {
    background-color: $brand_color;

    div.wrapper {
        padding: 2rem 2rem;
        display: flex;

        div.product {
            display: flex;
            margin-right: 5rem;

            div.img-container img {
                height: 5rem;
                vertical-align: middle;
                margin-right: 1rem;
            }

            h3 {
                color: white;
                font-size: 12px;
                text-transform: uppercase;
                margin-top: 10px;
                margin-left: 10px;

            }
        }
    }


}
</style>
