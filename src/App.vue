<template>
    <div id="app">
        <Welcome msg="Welcome to Augmedix Bangladesh"/>
    </div>
</template>

<script>
    import Welcome from './components/Welcome.vue'

    export default {
        name: 'App',
        components: {
            Welcome
        }
    }
</script>

<style lang="scss">
    #app {
        font-family:$sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: $primary;
        margin-top: 60px;
    }
</style>
