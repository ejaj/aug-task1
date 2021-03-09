<template>
    <div class="welcome">
        <h1>{{ msg }}</h1>
        <p>
            Augmedix Building, House# 17/C, Near Square Hospital,Panthapath, Dhaka - 1215,
        </p>
    </div>
</template>

<script>
    export default {
        name: 'Welcome',
        props: {
            msg: String
        },
        metaInfo: {
            title: 'Welcome'
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
    h3 {
        margin: 40px 0 0;
    }
    p {
        font-family: $sans-serif;
        font-size: $font_size_small;
    }
</style>