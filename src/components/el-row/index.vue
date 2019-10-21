<template>
  <div class="el-row">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'el-row',
  render(h) {
    return h(this.tag, {
      class: [
        'el-row'
      ]
    }, this.$slots.args)
  }
};
</script>
