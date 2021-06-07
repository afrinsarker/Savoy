<template>
    <div>
      <body>
        <Hero/>
        <Filters/>
        <Gallery/>
      </body>
        <!-- items -->
    </div>
</template>
<script>
import Hero from '@/components/Hero'
import Filters from '@/components/Filters'
import Gallery from '@/components/Gallery'

export default {
  data(){
    return{
      title:'',

    }
  },
  components:{

    Hero,
    Filters,
    Gallery,
 
  },
}
</script>

<style>

</style>
