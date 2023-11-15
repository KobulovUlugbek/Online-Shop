<template>
  <div class="v-catalog">
    <h1>Catalog</h1>
    <div class="v-catalog_list">
      <VCatalogItem />
    </div>
  </div>
</template>





<script>
import VCatalogItem from './V-catalog-item.vue'

export default {
  name: 'v-catalog',
  created () {},

  data () {
    return {
      products: [
        {
          image: 'logo.png',
          name: 'T-Shirt 1',
          price: 100,
          article: 'T1',
          available: true
        },
        {
          image: 'logo.png',
          name: 'T-Shirt 2',
          price: 100,
          article: 'T2',
          available: true
        },
        {
          image: 'logo.png',
          name: 'T-Shirt 3',
          price: 100,
          article: 'T3',
          available: true
        },
        {
          image: 'logo.png',
          name: 'T-Shirt 4',
          price: 100,
          article: 'T4',
          available: true
        },
        {
          image: 'logo.png',
          name: 'T-Shirt 5',
          price: 100,
          article: 'T5',
          available: true
        },
        {
          image: 'logo.png',
          name: 'T-Shirt 6',
          price: 100,
          article: 'T6',
          available: true
        },
        {
          image: 'logo.png',
          name: 'T-Shirt 7',
          price: 100,
          article: 'T7',
          available: true
        }
      ]
    }
  },

  props: {},

  methods: {},

  components: {
    VCatalogItem
  }
}
</script>






<style lang="scss">
.v-catalog {
  &_list {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
