<template>
  <div>
    <puik-alert
      title="title"
      variant="success"
      button-label="Action"
      link-label="Learn more"
      @click="handleClickAction"
      @click-link="handleClickLink"
      @close="handleClose"
    >
      This is the description of the success alert
    </puik-alert>
  </div>
</template>

<script setup lang="ts">
const handleClickAction = () => {
  console.log('Action button clicked')
}
const handleClickLink = () => {
  console.log('Link clicked')
}
const handleClose = () => {
  console.log('Alert closed')
}
</script>
