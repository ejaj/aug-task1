<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <p>
            Augmedix Building, House# 17/C, Near Square Hospital,Panthapath, Dhaka - 1215,
        </p>
    </div>
</template>

<script>
    export default {
        name: 'HelloWorld',
        props: {
            msg: String
        },
        metaInfo: {
            title: 'Hello World'
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 40px 0 0;
    }
</style>
