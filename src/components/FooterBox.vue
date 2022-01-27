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
            margin-top: 20px;
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

            // img{
            //     width:100%;
            //     object-fit: cover;
            // }
        }
        
        
    }
}
</style>