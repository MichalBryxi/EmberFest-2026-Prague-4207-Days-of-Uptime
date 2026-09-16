<script setup lang="ts">
import { computed } from 'vue'

const props = defineProps({
  image: {
    type: String,
  },
  class: {
    type: String,
  },
  backgroundSize: {
    type: String,
    default: 'cover',
  },
})

const style = computed(() => ({
  backgroundImage: props.image ? `url('${props.image}')` : undefined,
  backgroundSize: props.backgroundSize,
  backgroundPosition: 'center',
}))
</script>

<template>
  <div class="grid w-full h-full auto-rows-fr" style="grid-template-columns: 65% 35%">
    <div class="slidev-layout default" :class="props.class">
      <slot />
    </div>
    <div class="w-full h-full" :style="style" />
  </div>
</template>
