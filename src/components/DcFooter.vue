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
        <section class="header-bottom">
            <div class="header-container">
                <div class="button">
                    <button>Sign-up now!</button>
                </div>
                <div class="social-icons">
                    <span>Follow us</span>
                    <img src="../assets/img/footer-facebook.png" alt="Fb icon">
                    <img src="../assets/img/footer-twitter.png" alt="Fb icon">
                    <img src="../assets/img/footer-youtube.png" alt="Fb icon">
                    <img src="../assets/img/footer-pinterest.png" alt="Fb icon">
                    <img src="../assets/img/footer-periscope.png" alt="Fb icon">
                </div>
            </div>
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
        margin: 15px auto;

        div {
            width: calc(100% / 3);
            padding: 20px;
            h3 {
                color: white;
                padding: 5px;
            }

            li {
                color: grey;
                padding: 5px;
                
            }
        }
    }

    .footer-logo {
        margin-right: 15%;
    }
}

h3 {
    color: white;
    text-transform: uppercase;
    margin-top: 15px;
}
</style>
