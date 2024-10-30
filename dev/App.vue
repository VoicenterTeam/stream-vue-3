<template>
    <VideoStream
        video-id="9d5a2b7868d9562a57a98e7afdaf385a"
        class="video"
        autoplay
        muted
        loop
        controls
    />
</template>

<script lang="ts" setup>
import VideoStream from '@/VideoStream.vue'
</script>

<style>
.video {
  object-fit: cover;
  width: 100%;
  height: 100%;
}
</style>
