<template>
    <!-- Product container -->
    <div>
        <div class="mx-auto ">
            <main class="flex flex-col justify-evenly self-center justify-center wrapper h-screen">
                <h1 class="text-center">Products</h1>
            
                <div class="card-container h-4/6 flex justify-evenly" >
                    <div class="flex flex-col justify-between w-1/4 h-full card bg-zinc-400">
                        <div class="card-title text-center py-5">
                            Carrots
                        </div>
                        <div class="relative card-body">
                            <div class=" mb-5 flex justify-center">

                                <img src="../images/carrot.png" alt="carrot" width="150px">
                            </div>
                            <form class="flex justify-evenly space-x-12">
                                <div class="label space-y-2">
                                    <div>Type:</div>
                                    <div>Price:</div>
                                    <div>Quantity:</div>
                                </div>

                                <div class="results space-y-2">
                                    <em>Vegetable</em>
                                    <div class="cell">
                                        $4.82
                                    </div>
                                    <input type="number" value="0">
                                </div>
                                
                            </form>
                        </div>
                        <div class="card-footer text-center p-3">
                            <button class="btn ">Add to cart</button>
                        </div>
                    </div>

                    <div class="flex flex-col justify-between w-1/4 h-full card bg-zinc-400">
                        <div class="card-title text-center py-5">
                            Carrots
                        </div>
                        <div class="relative card-body">
                            <div class=" mb-5 flex justify-center">
                    
                                <img src="../images/carrot.png" alt="carrot" width="150px">
                            </div>
                            <form class="flex justify-evenly space-x-12">
                                <div class="label space-y-2">
                                    <div>Type:</div>
                                    <div>Price:</div>
                                    <div>Quantity:</div>
                                </div>
                    
                                <div class="results space-y-2">
                                    <em>Vegetable</em>
                                    <div class="cell">
                                        $4.82
                                    </div>
                                    <input type="number" value="0">
                                </div>
                    
                            </form>
                        </div>
                        <div class="card-footer text-center p-3">
                            <button class="btn ">Add to cart</button>
                        </div>
                    </div>

                    <div class="flex flex-col justify-between w-1/4 h-full card bg-zinc-400">
                        <div class="card-title text-center py-5">
                            Carrots
                        </div>
                        <div class="relative card-body">
                            <div class=" mb-5 flex justify-center">
                    
                                <img src="../images/carrot.png" alt="carrot" width="150px">
                            </div>
                            <form class="flex justify-evenly space-x-12">
                                <div class="label space-y-2">
                                    <div>Type:</div>
                                    <div>Price:</div>
                                    <div>Quantity:</div>
                                </div>
                    
                                <div class="results space-y-2">
                                    <em>Vegetable</em>
                                    <div class="cell">
                                        $4.82
                                    </div>
                                    <input type="number" value="0">
                                </div>
                    
                            </form>
                        </div>
                        <div class="card-footer text-center p-3">
                            <button class="btn ">Add to cart</button>
                        </div>
                    </div>
                </div>    
            </main>
        </div>
    </div>
</template>

<script>


export default{
    name: 'Products'
}
</script>