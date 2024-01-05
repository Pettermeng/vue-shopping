
<template>
    <header class="py-5 shadow-md shadow-gray-100">
        <div class="container mx-auto">
            <div class="flex items-center justify-between">
                <div class="hamburger-menu">
                    <div class="icon">
                        <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg" style="font-size: 24px; cursor: pointer;"><path d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"></path></svg>
                    </div>
                </div>
                <div class="logo">
                    <router-link to="/">
                        <img src="https://zandokh.com/image/catalog/logo/TEN11.png" class="w-48" alt="">
                    </router-link>
                </div>
                <div class="profile flex gap-2">
                    <span>Welcome</span>
                    <strong>Petter Meng</strong>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
    export default {
        name: "Header",
    };
</script>
