<template>
    <div class="back mx-100 h-screen bg-black">
        
    </div>
    <Products :inventory="inventory" :top="top"/>
</template>

<script>
import Products from './Products.vue';
export default{
    name: 'Home',
    components: {
        Products
    },
    props: {
        top: Number,
        inventory: Object,
    }
}
</script>

<style>

</style>