<script>
export default {
  name: 'el-col',
  props: {
    span: {
      type: Number
    },
    gutter: {
      type: Number
    }
  },
  render(h) {
    let classList = [];
    classList.push(`el-col-${this.span}`);
    return h(this.tag, {
      class: [
        'el-col',
        classList
      ]
    }, this.$slots.default)
  },
  created() {
    console.log('this');
    console.log(this);
  }
};
</script>
