<template>
    <div class="w-100 d-flex justify-content-end">
        <span class="fs-4 text-white">Seleziona un genere:</span>
        <select class="form-select w-25" name="selectGenres" id="selectGenres">
            <option value="" selected>All</option>
            <option value="pop">Pop</option>
            <option value="rock">Rock</option>
            <option value="jazz">Jazz</option>
            <option value="metal">Metal</option>
        </select>
    </div>
</template>

<script>
export default {
    name: "Select"
}
</script>

<style>

</style>