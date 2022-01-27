<template>
    <div class="container">

        <div class="content">
            --Content goes here ---
        </div>

    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
    .container {
        background-color: black;
        height: 200px;
        vertical-align: middle;
        line-height: 200px;
        color: #fff;
        .content {

            width: $width-container;
            margin:0 auto;
        }
    }

</style>
