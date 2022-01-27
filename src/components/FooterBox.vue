<template>
    <footer>
        <div class="container-info">
            <div class="content-info">
                <div class="content-info-text">
                    <div class="info-section">
                        <div class="title-section">
                            <h2>
                                DC COMICS

                            </h2>
                        </div>
                        <div class="items">
                            <ul>
                                <li>Characters</li>
                                <li>Comics</li>
                                <li>Movies</li>
                                <li>TV</li>
                                <li>Games</li>
                                <li>Videos</li>
                                <li>News</li>
                            </ul>
                        </div>
                    </div>
                    <div class="info-section">
                        <div class="title-section">
                            <h2>
                                SHOP
                            </h2>
                        </div>
                        <div class="items">
                            <ul>
                                <li>Shop DC</li>
                                <li>Shop DC Collectibles</li>
                            </ul>
                        </div>
                    </div>
                    <div class="info-section">
                        <div class="title-section">
                            <h2>
                                DC 

                            </h2>
                        </div>
                        <div class="items">
                            <ul>
                                <li>Terms Of Use</li>
                                <li>Privacy policy (New)</li>
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
                    </div>
                    <div class="info-section">
                        <div class="title-section">
                            <h2>
                                SITES

                            </h2>
                        </div>
                        <div class="items">
                            <ul>
                                <li>DC</li>
                                <li>MAD Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Visa</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="logo-dc">
                    <!-- <img src="../assets/dc-logo-bg.png" alt=""> -->
                </div>
            </div>
        </div>
        
        <div class="container-links">
            <div class="content-links">
                <div class="sign-up">
                    SIGN-UP NOW
                </div>
                <div class="social">
                    <div class="text">
                        FOLLOW US
                    </div>
                    <div id="facebook" class="social-network">
                        <img src="@/assets/footer-facebook.png" alt="">
                    </div>
                    <div id="twitter" class="social-network">
                        <img src="@/assets/footer-twitter.png" alt="">
                    </div>
                    <div id="youtube" class="social-network">
                        <img src="@/assets/footer-youtube.png" alt="">
                    </div>
                    <div id="pinterest" class="social-network">
                        <img src="@/assets/footer-pinterest.png" alt="">
                    </div>
                    <div id="periscope" class="social-network">
                        <img src="@/assets/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
.container-info{
    background: url('../assets/footer-bg.jpg');
    
    .content-info{
        width:$width-container;
        height: 300px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;

        .content-info-text{
            height: 100%;
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            align-content: flex-start;
            padding-top: 20px;
            color: #fff;
            flex-grow: 1;
            
            .info-section{
                padding-bottom: 15px ;
                margin-right: 25px;
            }
        }

        .logo-dc{
            flex-grow: 1;
            background: url('../assets/dc-logo-bg.png') no-repeat;
            background-size:cover;
            background-position: center;

        }
        
    }
}

.container-links{
    background-color: #303030;
    padding: 15px 0;

    .content-links{
        width:$width-container;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        .sign-up{
            border: 3px solid green;
            padding: 15px;
            color: $color-white;
        }
        .social{
            display: flex;
            align-items: center;
            justify-content: space-between;
            div{
                margin: 0 15px;
            }
            .text{
                color:$color-buttons-navbar;
            }
            .social-network{
                width:30px;
                img{
                    width:100%;
                }
            }
        }
    }
}
</style>