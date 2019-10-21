<script>
export default {
  name: "anchor",
  data() {
    const count = 6;
    let levelList = [];
    for (let i = 0; i < count; i++) {
      levelList.push(i);
    }
    return {
      levelList
    };
  },
  props: {
    level: {
      type: Number,
      required: true
    },
    title: {
      type: String,
      default: ''
    }
  },
  render(h) {
    return (<div>
      <h1>Anchor Component</h1>
    </div>)
  }
}
</script>

<style scoped>

</style>