<template>
  <div class="navbar1-container"></div>
</template>

<script>
export default {
  name: 'Navbar1',
  props: {
    logoSrc: {
      type: String,
      default:
        'https://aheioqhobo.cloudimg.io/v7/_playground-bucket-v2.teleporthq.io_/84ec08e8-34e9-42c7-9445-d2806d156403/fac575ac-7a41-484f-b7ac-875042de11f8?org_if_sml=1&force_format=original',
    },
    logoAlt: {
      type: String,
      default: 'logo',
    },
    link2: {
      type: String,
      default: 'Link2',
    },
    link3: {
      type: String,
      default: 'Link3',
    },
    action2: {
      type: String,
      default: 'Action 2',
    },
    link5: {
      type: String,
      default: 'Link5',
    },
    link1: {
      type: String,
      default: 'Link1',
    },
    link4: {
      type: String,
      default: 'Link4',
    },
    action1: {
      type: String,
      default: 'Action 1',
    },
  },
}
</script>

<style scoped>
.navbar1-container {
  width: 100%;
  display: flex;
  position: relative;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
</style>
