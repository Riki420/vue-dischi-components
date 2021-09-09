<template>
<!--HEADER-->
    <header class="container-fluid bg-head">
        <div class="row">
            <div class="col-12">
                <div class="container">
                    <div class="row py-2 d-flex align-items-center">
                        <div class="col-1">
                            <figure>
                                <img src="../assets/images/logo.png" alt="logo-spotify" class="img-fluid">
                            </figure>
                        </div>
                        <div class="col text-white">
                            <h1>SPOTIFY</h1>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>
    header{
        height: 100px;
        background-color: #2e3a46;;
    }
    
</style>