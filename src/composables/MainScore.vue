<script setup>
import useScore from '@/composables/useScore.js'
  const {score} = useScore()
</script>

<template>
  <span class="">Main Score: {{score}}</span>
</template>