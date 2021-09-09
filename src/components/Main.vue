<template>
<!--MAIN-->
  <main class="mt-4">
        <div class="container">
            <div class="row">
                <!--SELECT GENRES-->
                <div class="col">
                    <Select />
                </div>
            </div>
        </div>     
        <hr class="bg-white">
        <!--ALBUM SECTION-->
        <div class="container">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-5">
                <!--ALBUM CARD-->
                <Albumcard :albums="albums" v-for="(album, index) in albums" :key="index" :album="album"/>
            </div>
        </div>
      
  </main>

</template>

<script>
import Select from './Select.vue';
import Albumcard from './Albumcard.vue';
import axios from 'axios';
export default {
    name: "Main",
    components: {
        Select,
        Albumcard,
    },
    data(){
        return{
            albums: [],
            genres: []
        }
    },
    created(){
    axios.get('https://flynn.boolean.careers/exercises/api/array/music').then((res)=> {
        this.albums = res.data.response
        
        }
        
    
    )}
        
}
</script>

<style lang="scss" scoped>


</style>