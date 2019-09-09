<template>
    <div class="flex min-h-screen justify-center items-center text-center">
        <div class="card p-10 bg-green-500 rounded text-white font-mono">
            <p>This is the users dynamic link with ID {{ $route.params.id }}</p>
            <a href="/" class="no-underline hover:underline text-blue-500 text-lg">Home</a>
        </div>
    </div>
</template>