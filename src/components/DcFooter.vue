<template>
    <footer>
        <section class="list-menu">
            <div class="lists">
                <div class="list-left">
                    <h3>dc comics</h3>
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
                <div class="list-center">
                    <h3>dc</h3>
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
                <div class="list-right">
                    <h3>sites</h3>
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
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
}
</style>
