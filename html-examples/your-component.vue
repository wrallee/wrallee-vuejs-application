<template>
  <div>
    <span>
      <button>{{ message }}</button>
    </span>
  </div>
</template>

<script>
export default {
  data: {
    message: 'click this button'
  }
}
</script>

<style lang="css">
  span {
    font-size: 1.2em;
  }
</style>
