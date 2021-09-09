<template>
<!--MAIN-->
  <main class="mt-4">
        <div class="container">
            <div class="row">
                <!--SELECT GENRES-->
                <div class="col d-flex justify-content-end">
                        <span class="fs-bold text-white align-middle">Seleziona un genere:</span>
                        <select class="form-select w-25" name="selectGenres" id="selectGenres">
                            <option value="" selected>All</option>
                            <option value="pop">Pop</option>
                            <option value="rock">Rock</option>
                            <option value="jazz">Jazz</option>
                            <option value="metal">Metal</option>
                        </select>
                </div>
            </div>
        </div>     
        <hr class="bg-white">
        <!--ALBUM SECTION-->
        <div class="container">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 row-cols-lg-5">
                <div class="col bg-dark card py-2 text-center text-white">
                    <figure>
                        <img src="../assets/images/demo.jpg" alt="demo" class="img-fluid">
                    </figure>
                    <hr>
                    <h5>Demo</h5>
                    <address>Bon Jovi</address>
                </div>
            </div>
        </div>
      
  </main>

</template>

<script>
export default {
    name: "Main",
    component:{
    }
}
</script>

<style lang="scss" scoped>

.my-s-height{
    height: 200px;
}

</style>