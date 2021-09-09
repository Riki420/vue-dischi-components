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
                <div class="col">
                    <!--ALBUM CARD-->
                    <Albumcard />
                </div>
            </div>
        </div>
      
  </main>

</template>

<script>
import Select from './Select.vue';
import Albumcard from './Albumcard.vue';
export default {
    name: "Main",
    components:{
        Select,
        Albumcard
    }
}
</script>

<style lang="scss" scoped>


</style>