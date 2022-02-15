<template>
  <Care />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Care from '@/components/Care.vue' // @ is an alias to /src

export default defineComponent({
  name: 'Home',
  components: {
    Care
  }
})
</script>
