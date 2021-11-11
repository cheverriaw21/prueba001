<template>
    <div class="fixed-top">
        <b-navbar toggleable="lg" type="dark" variant="success">
            <b-navbar-brand href="#"> <b-icon icon="phone"></b-icon> Tienda CellPhone </b-navbar-brand>
            
            <!-- Right aligned nav items -->
            <b-navbar-nav class="mr-auto">
                <b-nav-form>
                    <b-button size="md" class="my-2 my-md-0" type="submit"><b-icon icon="search"></b-icon></b-button>
                    <b-form-input size="md" class="mr-md-2" placeholder="Search"></b-form-input>
                </b-nav-form>
            </b-navbar-nav>
            
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ml-auto">
                <b-nav-item href="#">Inicio</b-nav-item>
                <b-nav-item href="#">Estadísticas</b-nav-item>
                <b-nav-item href="#" ><b-icon icon="plus-circle-fill" font-scale="1.5"></b-icon></b-nav-item>
                <b-nav-item href="#" ><b-icon icon="cart-plus-fill" font-scale="1.5"></b-icon> 1</b-nav-item>     
            </b-navbar-nav>

            </b-collapse>
        </b-navbar>
    </div>

</template>

<script>
</script>

<style>

</style>