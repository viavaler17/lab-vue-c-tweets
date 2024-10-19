<script setup>
defineProps({
    message: String
});
</script>

<template>
    <p class="message">
        {{ message }}
      </p>
</template>


<style scoped></style>