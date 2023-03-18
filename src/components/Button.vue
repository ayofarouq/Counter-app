<script setup>
const {text} = defineProps(['text'])
    
</script>

<template>
    <button>
        {{ text }}
    </button>
</template>