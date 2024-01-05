<template>
  <main>
    <HomeSlider />
    <CollectionCard2 />
    <CollectionCard4 />
  </main>
</template>


<script>
  import HomeSlider      from "../components/section/HomeSlider.vue"
  import CollectionCard2 from "../components/section/CollectionCard2.vue"
  import CollectionCard4 from "../components/section/CollectionCard4.vue"

  export default {
    name: "App",
    components: { 
      HomeSlider,
      CollectionCard2,
      CollectionCard4
    },
    methods: {},
  };
</script>