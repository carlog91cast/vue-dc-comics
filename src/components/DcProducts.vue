<template>
    <main>
        <div class="product-container">
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
        </div>
    </main>
</template>

<script>
export default {
    name: 'DcProduct',
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
                    text: 'Shop Location',
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


.product-container {
    background-color: $brand_color;

    #wrapper {
        padding: 2rem 2rem;
        display: flex;

        .product {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 80px;
            width: calc(100% / 5);

            .img-container {
                display: flex;
                margin-left: 5rem;
                

                img {
                    height: 5rem;
                }

                h3 {
                    color: white;
                    font-weight: 100;
                    text-transform: uppercase;
                    font-size: 16px;
                    margin-top: 1rem;
                    margin-left: 10px;
                }
            }

        }
    }


}
</style>
