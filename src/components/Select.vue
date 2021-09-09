<template>
    <div class="w-100 d-flex justify-content-end">
        <span class="fs-4 text-white mx-4">Seleziona un genere:</span>
        <select class="form-select w-25" name="selectGenres" id="selectGenres">
            <option value="" selected>All</option>
            <option v-for="(genre, index) in genres" :key="index" :value="genre"> {{ genre }} </option>
        </select>
    </div>
</template>

<script>
export default {
    name: "Select",
    props: ['genre'],
    data(){
        return{
        }
    }
}
</script>

<style>

</style>