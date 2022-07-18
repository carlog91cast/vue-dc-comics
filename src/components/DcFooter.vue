<template>
    <footer>
        <section class="list-menu">
            <div class="lists">
                <div>
                    <h3>dc comics</h3>
                    <ul>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li>characters</li>
                        <li>characters</li>
                    </ul>
                </div>
                <div>
                    <h3>dc</h3>
                    <ul>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                    </ul>
                </div>
                <div>
                    <h3>sites</h3>
                    <ul>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                    </ul>
                </div>
            </div>
            <div class="footer-logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </section>
        <section class="footer-bottom">
            <nav class="footer-nav">
                <div class="button">
                    <button class="btn btn primary" >Sign-up now!</button>
                </div>
                <h3 class="fs-5">Follow us</h3>
                <ul class="social-icons">
                    <li>
                        <img src="../assets/img/footer-facebook.png" alt="Fb icon">
                    </li>
                    <li>
                        <img src="../assets/img/footer-twitter.png" alt="Fb icon">
                    </li>
                    <li>
                        <img src="../assets/img/footer-youtube.png" alt="Fb icon">
                    </li>
                    <li>
                        <img src="../assets/img/footer-pinterest.png" alt="Fb icon">
                    </li>
                    <li>
                        <img src="../assets/img/footer-periscope.png" alt="Fb icon">
                    </li>
                </ul>
            </nav>
        </section>
    </footer>
</template>

<script>
export default {
    name: 'DcMain',
    data() {
        return {
            iconsFooter: [

            ]
        }
    }

}


</script>

<style lang="scss" scoped>
@import '../style/common.scss';
@import '../style/variables.scss';

.list-menu {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    display: flex;
    ;

    .lists {
        display: flex;
        justify-content: space-between;
        margin: 20px auto;

        div {
            width: calc(100% / 4);
            padding: 25px;

            h3 {
                color: white;
                padding: 5px;
            }

            li {
                color: grey;
                padding: 1px;

            }
        }
    }

    .footer-logo {
        margin-right: 15%;
        img{
            height:30rem;
            object-fit: contain;
            object-position: center;
        }
    }
}

h3 {
    color: white;
    text-transform: uppercase;
    margin-top: 15px;
}

.footer-bottom {
    background-color: $footer_color;

    .footer-nav {
        width: 70%;
        margin: 0 auto;
        padding: 0.5rem 2rem;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100px;

        button {
            color:white;
            background-color: $footer_color;
            border: 2px solid $brand_color;
        }

        h3 {
            text-transform: uppercase;
            color: $brand_color;
            margin-bottom: 13px;
            margin-left: 45%;

        }

        .social-icons {
            display: flex;

            li {
                margin-right: 1rem;
                font-size: 0.8rem;

                // .bottom-line {
                //     color: $brand_color;
                //     border-bottom: 2px solid $brand_color;
                // }
            }



        }
    }

}
</style>
