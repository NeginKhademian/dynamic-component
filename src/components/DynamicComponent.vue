<script>
export default {
  render(createElement) {
    return createElement(this.dynamicComponent, {});
  },
  computed: {
    dynamicComponent() {
      return {
        inheritAttrs: true,
        template: `<div>test</div>`,
      };
    },
  },
};
</script>
