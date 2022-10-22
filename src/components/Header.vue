<script>
export default {
  name: 'HeaderVue',
  props: {
    level: {
      type: Number,
      required: true,
    },
  },
  render: function (createElement) {
    // console.log(this.$slots.default);
    return createElement('h' + this.level, this.$slots.default);
  },
};
</script>
