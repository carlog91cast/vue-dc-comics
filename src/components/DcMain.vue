<template>
    <main>
        <section class="jumbotron">
            <div class="jumbotron-content">
                contents goes here
            </div>
        </section>

        <section class="menu-icon">
            <ul class="list-icon">
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <p>digital comics</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <p>merchandise</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <p>shop locator</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <p>subscriptions</p>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <p>dc power visa</p>
                </li>
            </ul>
        </section>
    </main>
</template>

<script>
export default {
    name: 'DcMain',
    data() {
        return {
            icons: [

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

.menu-icon {
    background-color: $brand_color;
    width: 100%;
    height: 15vh;

    .list-icon {
        width: 70%;
        margin: 0 auto;
        display: flex;

        li {
            width: calc(100% / 5);
            display: flex;
            align-items: center;
            margin-top: 30px;
            

            img {
                width: 20%;
                height: 50px;

            }

            p {
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
