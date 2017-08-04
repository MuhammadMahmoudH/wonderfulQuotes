<template>
  <div class="container">
  <app-quote-grid :quotes="quotes"></app-quote-grid>
  </div>
</template>

<script>
  import QuoteGride from './Components/QuoteGrid.vue';
export default {
    data(){
        return{
            quotes:['just a Quote to See Something','Mahrous','Bakr','Hamdy','Mohtaseem','Hanafy'],
            MaxQuotes:10
        }
    },
    components:{
        appQuoteGrid:QuoteGride
    }
}
</script>

<style>

</style>
