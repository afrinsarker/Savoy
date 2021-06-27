<template>
    <div>
      <body>
        <Hero/>
        <FiltersComponent/>
        <Gallery/>
      </body>
        <!-- items -->
    </div>
</template>
<script>
import Hero from '@/components/Hero'
import FiltersComponent from '@/components/shops/FiltersComponent'
import Gallery from '@/components/Gallery'

export default {
  data(){
    return{
      title:'',

    }
  },
  components:{
    Hero,
    FiltersComponent,
    Gallery,
 
  },
}
</script>

<style>

</style>
