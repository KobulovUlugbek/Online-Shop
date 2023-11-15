<template>
    <div class="v-main-wrapper">
        <p></p>
        <VCatalog />
        <VCart />
    </div>
</template>



<script>
import VCatalog from './V-catalog.vue';
import VCart from './V-cart.vue';


export default{
    name: 'v-main-wrapper',
    components: {
    VCatalog,
    VCart
},
    props: {},
    data(){
        return{
            
        }
    },
/*     computed: {},

    methods: {},

    watch: {},

    mounted: {}, */
}

</script>





<style>

.v-main-wrapper{
    /* display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center; */
    max-width: 900px;
    margin: 0 auto;
}


</style>