<template>
    <header class="fixed h-1/11 top-0 left-0 w-full bg-black text-white p-4 z-50 flex items-center justify-between">
        <div class="flex items-center space-x-4 overflow-hidden">
            <a href="./">
                <img src="/logo.png" class="h-[7svh] logo-top object-cover rounded-lg invert-100"
                alt="Catastrophic Studios Logo"></img>
            </a>
            <span class="font-bold text-xl md:text-2xl lg:text-3xl">Catastrophic Studios</span>
        </div>

        <nav class="flex mr-10">
            <a href="./" class="px-5 py-2 text-xl">Home</a>
            <a href="#" class="px-5 py-2 text-xl">Our Games</a>
            <a href="about.html" class="px-5 py-2 text-xl">About Us</a>
            <a href="#" class="px-5 py-2 text-xl">Contact</a>
        </nav>
    </header>
</template>

<script setup lang="ts">
</script>

<style scoped>
* {
    -webkit-user-drag: none;
    user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
}
a {
    background-color: rgba(0,0,0,0);
    color: white;
    transition: 0.2s;
}
a:hover {
    border-radius: 10px;
    background-color: rgb(36, 36, 36);
    color: rgb(194, 194, 194);
    transition: 0.2s;
}
</style>