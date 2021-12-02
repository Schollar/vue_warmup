<template>
    <div>
        <h1>Our Menu</h1>
        <section id="menu_section">
            <menu-item></menu-item>
        </section>
    </div>
</template>

<script>
    import MenuItem from './MenuItem.vue'

    export default {
       name: "home-page-body",
       components: {
           MenuItem
           }
    }
</script>

<style scoped>
 #menu_section {
     display: grid;
     place-items: center;
 }
</style>