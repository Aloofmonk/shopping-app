<template>
  <div>
    <nav class=" mx-100 p-7 bg-green-400 fixed r-0">
      <div class="flex items-center justify-between">
    
        <div class="l-div">
          <li class="list-none flex space-x-6">
            <ul>Home</ul>
            <ul>Products</ul>
            <ul>Past Orders</ul>
          </li>
        </div>
    
        <div class="r-div ml-10">
          <span @click="toggle()" class="cursor-pointer	">
            <font-awesome-icon icon="cart-shopping" class="text-2xl pl-3" />({{0}})
          </span>
        </div>
      </div>
    </nav>

    <aside v-if="showSidebar">
      <div class="cart bg-black h-screen fixed text-white">
        <div class="asideHeading flex justify-between">
          <div class="cartIcon mt-5 ml-4">
            Cart<font-awesome-icon icon="cart-shopping" class="text-2xl pl-3" />
          </div>
          <div class="close cursor-pointer" @click="toggle()">
            <font-awesome-icon icon="xmark" class="text-3xl mr-11 mt-5"/>
          </div>
        </div>
        <div class="subHead flex justify-evenly mt-6 ">
          <div> 
            
          </div>
          <h1>Product</h1>
          <h1>Price</h1>
          <h1>Qty</h1>
          <h1>Total</h1>
          <div> 
            
          </div>
        </div>
        <div class="subHeadItems flex justify-evenly mt-3">
          <div> 
            <font-awesome-icon icon="carrot" class="text-3xl" />
          </div>
          <p>Carrot</p>
          <p>$1.00</p>
          <p></p>
          <p>$1.00</p>
          <div> 
            <font-awesome-icon icon="xmark" class="text-2xl" />
          </div>
        </div>
        <div class="noItems text-center mt-7">
          <p>No items in cart</p>
        </div>
        <div class="totalCheck flex justify-between">
          <div class="total">
            <h2>Total: <span>$1.00</span></h2>
          </div>
          <div class="check">
            <button>Checkout</button>
          </div>
        </div>
      </div>
    </aside>

    <Home :inventory="inventory" :top="top"/>
  </div>
</template>

<script>
import Home from './components/Home.vue';

export default{
  name: 'App',
  components: {
    Home
  },
  data() {
    return {
      inventory: {

        carrots: 0,
        pineapples: 0,
        cherries: 0,
      },
      cart: {
        carrots: 0,
        pineapples: 0,
        cherries: 0,
      },
      showSidebar: false,
      top: 9,
    }
  },
  methods: {
    // addToCart(type) {
    //   this.cart[type] += this.inventory[type]
    //   this.inventory[type] = 0
    //   console.log(this.cart)
    // },
    toggle(){
      this.showSidebar = !this.showSidebar
    }
  },
  
}
</script>

<style>

</style>
