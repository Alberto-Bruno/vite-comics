<script>
export default {
    data() {
        return {

        }
    }

}
</script>

<template>
    <footer>
        <div class="bg-blue">
            <div class="container">
                <div class="cols">

                </div>
            </div>
        </div>

        <div class="bg-image">
            <div class="container">
                <div class="footer-sx"></div>
                <div class="col">
                    <h4>DC COMICS</h4>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>Tv</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h4>SHOP</h4>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>

                <div class="col">
                    <h4>DC</h4>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy policy(New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>

                <div class="col">
                    <h4>SITES</h4>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>Dc Power Visa</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="bg-black">
            <div class="container">
                <button>SING-UP NOW&#33;</button>

                <div class="social-link">
                    <ul>
                        <h3>FOLLOW US</h3>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-facebook.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-periscope.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-facebook.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-facebook.png" alt="">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>


<style lang="scss" scoped>
@use '../styles/variables.scss' as*;



.bg-image {
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;

    .container {
        background-image: url('../assets/img/dc-logo-bg.png');
        background-position: right center;
        background-repeat: no-repeat;
        display: flex;

        .footer-sx {
            display: flex;
            margin: 10px;
        }

        .col {
            margin: 60px 5px;
            line-height: 2;

            li {
                color: gray;
                font-size: 15px;
            }

            h4 {
                color: white;
                text-transform: uppercase;
                font-weight: 800;
                font-family: 'Roboto', sans-serif;
            }

            ul {
                list-style: none;
            }
        }
    }
}

.bg-black {
    background-color: #303030;
    padding: 30px;


    button {
        padding: 10px;
        background-color: transparent;
        border: 2px solid $color-blue;
        color: white;
        cursor: pointer;
    }

    .social-link {
        display: flex;
        justify-content: flex-end;

        ul {
            display: flex;
            flex-direction: row;
            align-items: center;
            list-style: none;

            h3 {
                color: $color-blue;
                font-family: 'Roboto', sans-serif;
                font-weight: 500;
            }

            li {
                list-style: none;

                img {
                    max-width: 100%;
                    height: 35px;
                    margin: 0 0.3rem;
                }
            }
        }
    }

}
</style>