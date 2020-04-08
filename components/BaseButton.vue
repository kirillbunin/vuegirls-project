<template>
  <button class="button" :class="{ 'button--green': type }" @click="click">
    <slot />
  </button>
</template>

<script>
export default {
  props: {
    type: { type: String, required: false, default: 'žádný' }
  },
  methods: {
    click() {
      alert(this.type)
    }
  }
}
</script>

<style>
.button {
}
</style>
