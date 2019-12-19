<template>
    <div>
        <Header />
        <router-view/>
    </div>
</template>

<script>
    import Header from '@/components/Header.vue'

    export default {
        name: 'home',
        components: {
            Header
        }
    }
</script>

<style>

body{
    padding: 0;
    margin: 0;
    color: #2c3e50;
    text-align: center;
    font-family:'Avenir', Helvetica, Arial, sans-serif;
}
#nav a.router-link-exact-active {
color: #42b983;
}

</style>
