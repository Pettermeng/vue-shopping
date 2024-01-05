


<template>
    <section>
        <div class="container mx-auto">
            <div class="grid grid-cols-2 grid-flow-col gap-6 mb-4">
                <div class="left font-semibold text-2xl">
                    New Product
                </div>
                <div class="right text-right hover:text-pink-600">
                    <router-link to="/">View More</router-link>
                </div>
            </div>
            <div class="grid grid-cols-4 grid-flow-col gap-6">
                <figure v-for="(product, index) in products" :key="index">
                    <router-link to="/collection">
                        <div class="thumbnail mb-4 overflow-hidden">
                            <img :src="product.thumbnail" class="w-full hover:scale-110 ease-in-out duration-700" alt="">
                        </div>
                        <div class="detail">
                            <div class="pricing flex gap-5">
                                <div class="regular ">
                                    <strike>$35</strike>
                                </div>
                                <div class="sale text-pink-600">$15</div>
                                <div class="discount">45%</div>
                            </div>
                            <div class="name text-gray-500 mb-2">
                                {{ product.name }}
                            </div>
                            <div class="color flex gap-2">
                                <div class="p-2 bg-black w-1"></div>
                                <div class="p-2 bg-red-500 w-1"></div>
                                <div class="p-2 bg-blue-500 w-1"></div>
                            </div>
                        </div>
                    </router-link>
                </figure>     
            </div>
        </div>
    </section>
</template>

<script>
    let products = [
        {
            thumbnail : 'https://zandokh.com/image/cache/catalog/products/2023-11/2222306196/Christmas/Open-Back-Top%20(2)-cr-450x672.jpg',
            name      : 'Knit Cardigan'
        },
        {
            thumbnail : 'https://zandokh.com/image/cache/catalog/products/2023-11/2222307231/Christmas/High-Wast-Trouser%20(3)-cr-450x672.jpg',
            name      : 'Bomber Jackets'
        },
        {
            thumbnail : 'https://zandokh.com/image/cache/catalog/products/2023-12/2122311257/Vest%20(3)-cr-450x672.jpg',
            name      : 'Abstract Jaquard Sweater'
        },
        {
            thumbnail : 'https://zandokh.com/image/cache/catalog/products/2023-09/2122308223/Christmas/8J6A8744-cr-450x672.jpg',
            name      : 'Knitted Vest'
        },
    ];
    export default {
        name: "CollectionCard4",
        data() {                                   
            return {
                products: products
            }
        }
    };
</script>