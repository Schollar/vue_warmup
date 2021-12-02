<template>
    <div>
        <h1>Item Title</h1>
        <img src='http://placekitten.com/75' alt=''/>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perferendis earum quisquam velit? Eos, ut in? Ratione ab quia, veniam dolore dolor quaerat beatae sapiente, esse nulla dolores itaque adipisci voluptatem.</p>
        <h2>Price: $50</h2>
    </div>
</template>

<script>

    export default {
        name: 'menu-item'
    }
</script>

<style  scoped>

    div {
        margin-top: 50px;
        display: grid;
        place-items: center;
        width: 300px;
        border: 1px solid black;
        border-radius: 10px;
    }

</style>