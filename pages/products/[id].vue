<template>
    <div>
        <p>Product Details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat amet nam repudiandae accusamus, soluta sequi pariatur eveniet non at. Amet?</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style scoped>

</style>