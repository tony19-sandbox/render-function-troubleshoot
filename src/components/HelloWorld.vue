<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: 'hi'
    }
  },
  render(h) {
    return h('div', this.msg)
  }
};
</script>