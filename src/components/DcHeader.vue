<template>
    <div class="header-container">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <nav class="header-nav">
            <ul class="header-list">
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </div>
</template>

<script>
// export default {
//     name: 'PageHeader',
//     data() {
//         return {
//             navItems: [
//                 {
//                     text: 'CHARACTERS',
//                     url: '#',
//                 },
//                 {
//                     text: 'COMICS',
//                     url: '#',
//                 },
//                 {
//                     text: 'MOVIES',
//                     url: '#',
//                 },
//                 {
//                     text: 'TV',
//                     url: '#',
//                 },
//                 {
//                     text: 'GAMES',
//                     url: '#',

//                 },
//                 {
//                     text: 'COLLECTIBLES',
//                     url: '#',

//                 },
//                 {
//                     text: 'VIDEOS',
//                     url: '#',

//                 },
//                 {
//                     text: 'FANS',
//                     url: '#',

//                 },
//                 {
//                     text: 'NEWS',
//                     url: '#',

//                 },
//                 {
//                     text: 'SHOP',
//                     url: '#',

//                 }
//             ],
//         };
//     }
// }

</script>

<style lang="scss" scoped>
@import '../style/common.scss';
@import '../style/variables.scss';

.header-container {
    width: 70%;
    margin: 0 auto;
    padding: 0.5rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100px;

    .logo {
        img {
            width: 50px;
        }
    }

    .header-nav {
        .header-list {
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
