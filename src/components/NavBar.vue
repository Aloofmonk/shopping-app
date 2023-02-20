<template>
    <nav class=" mx-100 p-7 bg-green-400 ">
        <div class="flex items-center justify-between">

            <div class="l-div">
                <li class="list-none flex space-x-6">
                    <ul>Home</ul>
                    <ul>Products</ul>
                    <ul>Past Orders</ul>
                </li>
            </div>
        
            <div class="r-div ml-10">
                <span>
                    Cart(0)
                </span>
            </div>
        </div>
    </nav>
</template>

<script>
export default{
    name: 'NavBar'
}
</script>