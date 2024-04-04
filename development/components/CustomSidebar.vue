<template>
  <div
    class="custom-date-grid-event"
    :style="{
      width: '100%',
      height: '100%',
      border: '2px solid black',
      borderRadius: '4px',
      backgroundColor: 'red',
      color: '#fff',
    }"
  >
    is open : {{ isOpen }}
  </div>
</template>

<script lang="ts" setup>
defineProps({
  isOpen: {
    type: Boolean,
    required: true,
  },
})
</script>

<style lang="scss"></style>
