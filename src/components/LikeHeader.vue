<template>
  <div>
    <slot></slot>
  </div>
</template>

<script>
export default {
    data() {
        return {
            user: {
                firstName: 'Jack',
                lastName: 'Dnald'
            }
        }
    }
};
</script>

<style scoped>

  h1 {
      color: red;
  }

</style>