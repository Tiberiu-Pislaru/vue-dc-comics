<template>
    <div class="container-marketing">
        <div class="content-marketing">

            <div class="box-marketing">
                <div class="img-marketing">
                    <img src="@/assets/buy-comics-digital-comics.png" alt="">
                </div>
                <div class="text-marketing">
                    DIGITAL COMICS
                </div>
            </div>
            <div class="box-marketing">
                <div class="img-marketing">
                    <img src="@/assets/buy-comics-merchandise.png" alt="">
                </div>
                <div class="text-marketing">
                    DC MERCHANDISE
                </div>
            </div>
            <div class="box-marketing">
                <div class="img-marketing">
                    <img src="@/assets/buy-comics-subscriptions.png" alt="">
                </div>
                <div class="text-marketing">
                    SUBSCRIPTION
                </div>
            </div>
            <div class="box-marketing">
                <div class="img-marketing">
                    <img src="@/assets/buy-comics-shop-locator.png" alt="">
                </div>
                <div class="text-marketing">
                    COMIC SHOP LOCATOR
                </div>
            </div>
            <div class="box-marketing">
                <div class="img-marketing">
                    <img src="@/assets/buy-dc-power-visa.svg" alt="">
                </div>
                <div class="text-marketing">
                    DC POWER VISA
                </div>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
    .container-marketing{
        background-color: $color-buttons-navbar;
        color: $color-white;
        padding: 10px 0;
        font-size: 10px;

        .content-marketing{
            width: $width-container;
            margin:0 auto;
            display: flex;
            justify-content: space-around;

            .box-marketing{
                display: flex;
                align-items: center;
                

                .img-marketing{
                    width: 50px;

                    img{
                        width: 100%;
                        object-fit: cover;
                    }
                }
                .text-marketing {
                    padding-left: 10px;
                }
            }
        }
    }

</style>