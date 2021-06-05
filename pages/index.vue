<template>
    <div>
      <body>
        <Hero/>
        <Filters/>
        <Gallery/>
      </body>
        <!-- items -->
      <div>
        <Footer/>
      </div>
        
    </div>
</template>
<script>
import Hero from '@/components/Hero'
import Filters from '@/components/Filters'
import Gallery from '@/components/Gallery'
import Footer from '@/components/Footer'
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
    Footer,
  },
}
</script>

<style>

</style>
