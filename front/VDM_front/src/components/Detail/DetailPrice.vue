<template>
  <div>{{ prix }} €</div>
</template>

<script>
export default {
  props: {
    prix: { type: [String, Number], required: true },
  },
}
</script>
