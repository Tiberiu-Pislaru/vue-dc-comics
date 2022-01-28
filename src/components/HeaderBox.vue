<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="@/assets/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li v-for="button in buttons" :key='button.id'>{{button.name}}</li>
                    
                </ul>
            </nav>

        </div>
        
    </header>
</template>

<script>
export default {
    props: {
       buttons:Array
    },

}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

header {
    display: flex;
    justify-content: space-between;

    .container {

        display: flex;
        justify-content: space-between; 
        width: $width-container;
        margin:0 auto;
        nav {
            display: flex;
            align-content: center;
            
            ul{
                display: flex;
                align-items:center;
                list-style: none;
                li{
                    padding: 0 10px; 
                    height:100%;
                    display: flex;
                    align-items: center;
                    border-bottom: 5px solid transparent;

                    &:hover{
                        color: $color-buttons-navbar;
                        border-bottom: 5px solid $color-buttons-navbar;
                    }
                }
            }
        }

    }
    
}

</style>
