<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>
<template>
    <div class="Majifer-tittle">
        <h3>
            You’ve successfully created a project with
            <a target="_blank" href="https://vitejs.dev/">Vite</a> +
            <a target="_blank" href="https://vuejs.org/">Vue 3</a>.
        </h3>
    </div>

</template>