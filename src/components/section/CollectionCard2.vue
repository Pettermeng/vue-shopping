<template>
    <!-- <slick
        ref="slick"
        :options="slickOptions"
        @afterChange="handleAfterChange"
        @beforeChange="handleBeforeChange"
        @breakpoint="handleBreakpoint"
        @destroy="handleDestroy"
        @edge="handleEdge"
        @init="handleInit"
        @reInit="handleReInit"
        @setPosition="handleSetPosition"
        @swipe="handleSwipe"
        @lazyLoaded="handleLazyLoaded"
        @lazyLoadError="handleLazyLoadError">
        <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
        <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
        <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
        <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
        <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
    </slick> -->

    <section class="mb-10">
        <div class="container mx-auto">
            <div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-2 gap-6">
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
import 'slick-carousel/slick/slick.css';
    export default {
        name: "CollectionCard2",
    };
</script>