<script seetup>
</script>

<template>
    <main>
        Hi there! This is Layout.vue
        <slot />
    </main>
</template>

<style scoped>
header {
    background-color: #333;
    color: white;
    padding: 1rem;
    width: 100%;
}
main {
    width: 100%;
}
.logo {
    background-color: #333;
    color: white;
    padding: 1rem;
}
.left-sidebar {
    background-color: #f4f4f4;
    width: 200px;
    height: 100vh;
}
</style>