<template>
  <div>
    <nuxt />
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  head: {
    bodyAttrs: {
      class: 'admin',
    },
  },
})
</script>
