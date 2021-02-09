<template>
    <div class="navbar">
        <v-container>
            <div class="navbar__content">
                <hr class="redline1">
                <div class="menu">
                    <div class="menu__items">
                        <ul>
                            <li>
                                <a href="#">Напитки</a>
                            </li>
                            <li>
                                <a href="#">Супы</a>
                            </li>
                            <li>
                                <a href="#">Гарниры</a>
                            </li>
                            <li>
                                <a href="#">Морепродукты</a>
                            </li>
                            <li>
                                <a href="#">Десерты</a>
                            </li>
                        </ul>
                    </div>
                    <div class="menu__cart">
                        <img src="@/assets/img/cart-icon.svg" alt="cart-icon">
                    </div>
                </div>
                <hr class="redline2">
            </div>
        </v-container>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss">
    .navbar {
        background-color: #000000;

        .navbar__content {
            .redline1 {
                color: #FF0000;
                margin-bottom: 9px;
            }

            .menu {
                display: flex;
                justify-content: space-between;

                &__items {
                    ul {
                        display: flex;
                        list-style-type: none;

                        li {
                            margin-right: 16px;

                            a {
                                color: #FFFFFF;
                                text-decoration: none;
                                font-size: 18px;
                                font-weight: bold;
                            }
                        }
                    }
                }
            }
        }

        .redline2 {
            color: #FF0000;
            margin-bottom: 26px;
        }
    }

    .v-application p {
        margin-bottom: 0px !important;

    }

    .v-application ul {
        padding-left: 0px !important;

    }
</style>