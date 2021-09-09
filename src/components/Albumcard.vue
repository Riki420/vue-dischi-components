<template>
    <div class="col mt-3">
        <div class="card my-s-height bg-dark py-2 text-center text-white pointer">
            <div class="card-body">
                <figure>
                    <img :src="album.poster" :alt="album.title" class="img-fluid">
                </figure>
                <hr>
                <h5>{{ album.title }}</h5>
                <address>{{ album.author }}</address>
            </div>
        </div>     
    </div>
        
</template>

<script>
export default {
    name: "Albumcard",
    props: ['album']
}
</script>

<style lang="scss" scoped>
.my-s-height{
    height: 380px;
}

</style>