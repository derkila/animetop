<template>
    <HeaderComp page='about'/>
    <h1> contact </h1>
    <h2> alex@lordshadow.net </h2>
    <h2> <a href="https://lordshadow.net"> website </a> </h2>
    <h2> <a href="https://YouTube.com/@Derkila"> YouTube </a> </h2>
</template>

<script>
import HeaderComp from '../components/HeaderComp.vue';

export default {
    name: 'AboutPage',
    components: {
        HeaderComp,
    },
}
</script>


<style scoped>



h1 {
    padding-top: 10%;
    color: gray;
    text-align: center;
}
h2 {
    padding-top: 3%;
    color: white;
    text-align: center;
}
a:link,
a:visited,
a:hover,
a:active {
    font-weight: bold;
    color: white;
    text-decoration: none;
}
</style>
