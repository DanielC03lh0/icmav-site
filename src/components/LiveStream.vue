<template>
    <div class="aspect-w-16 aspect-h-9 rounded-lg overflow-hidden shadow-lg" data-aos="fade-up">
        <iframe :src="`https://www.youtube.com/embed/live_stream?channel=${channelId}`" frameborder="0" allowfullscreen
            class="w-full h-full"></iframe>
    </div>
</template>

<script setup>
const channelId = '@igrejaICMAV'
</script>
  
