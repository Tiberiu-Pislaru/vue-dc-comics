<template>
    <div class="container-serie">

        <div class="current-series">
            CURRENT SERIES
        </div>

        <div class="container-card">

            <div class="card" v-for="(card, index) in cards" :key='index'>
                <div class="img-card">
                    <img :src="card.thumb" alt="">
                </div>
                <div class="title-card">
                    {{card.series}}
                </div>
            </div>
            
        </div>

        <div class="more">
            LOAD MORE
        </div>
    </div>
</template>

<script>
export default {
    props: {
       cards:Array
    },
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
.container-serie{
    position: relative;
    padding: 20px 0;
    width:$width-container;
    margin: 0 auto;
    text-align: center;
    
    .current-series{
        padding: 10px;
        background: $color-buttons-navbar;
        position: absolute;
        top: 0;
        left: 0;
        transform: translate(0,-50%);
    }
    .container-card{
        display: flex;
        flex-wrap: wrap;
        justify-content:space-around;

        .card{
            width:calc((100% / 6) - 20px);
            margin: 30px 0;
            text-align: start;

            .img-card{
                height: 150px;
                margin-bottom: 15px;
                overflow: hidden;
                
                img{
                    width: 100%;
                    object-fit: contain;
                }
            }

            .title-card{
                color:$color-white;
                font-size:12px;
            }
        }
    }

    .more{
        background: $color-buttons-navbar;
        padding: 10px 30px;
        display: inline-block;
        
    }
}
</style>