<template>
    <div class="back mx-100 h-screen bg-black">
        <NavBar/>
    </div>
    <Products/>
</template>

<script>
import NavBar from './NavBar.vue';
import Products from './Products.vue';
    export default {
        name: 'Home',
        components: {
            NavBar,
            Products
        }
    }
</script>

<style>

</style>