<template>
    <section class="mb-10">
        <div class="container mx-auto">
            <div class="grid grid-cols-2 grid-flow-col gap-6">
                <figure>
                    <div class="thumbnail mb-4">
                        <img src="https://zandokh.com/image/catalog/banner/2023/fall-winter/women.jpg" class="w-full" alt="">
                    </div>
                    <div class="detail text-center p-3 border border-slate-500 hover:border-slate-400 cursor-pointer font-semibold hover:text-blue-900">
                        <router-link to="/collection">Women Collections</router-link>
                    </div>
                </figure>                
                <figure>
                    <div class="thumbnail mb-4">
                        <img src="https://zandokh.com/image/catalog/banner/2023/fall-winter/men.jpg" class="w-full" alt="">
                    </div>
                    <div class="detail text-center p-3 border border-slate-500 hover:border-slate-400 cursor-pointer font-semibold hover:text-blue-900">
                        <router-link to="/collection">Women Collections</router-link>
                    </div>
                </figure>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "CollectionCard2",
    };
</script>