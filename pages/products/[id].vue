<template>
    <div>
        <p>Product details for {{ id  }}</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusantium mollitia perspiciatis, nobis minus aut ipsa porro non.
        Ab vero modi architecto qui id. Ipsam aperiam at amet repudiandae iste ipsum!</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    
    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>