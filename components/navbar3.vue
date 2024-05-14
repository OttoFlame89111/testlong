<template>
  <div class="navbar3-container"></div>
</template>

<script>
export default {
  name: 'Navbar3',
  props: {
    logoAlt: {
      type: String,
      default: 'logo',
    },
    link3: {
      type: String,
      default: 'Link3',
    },
    link5: {
      type: String,
      default: 'Link5',
    },
    link4: {
      type: String,
      default: 'Link4',
    },
    logoSrc: {
      type: String,
      default:
        'https://aheioqhobo.cloudimg.io/v7/_playground-bucket-v2.teleporthq.io_/84ec08e8-34e9-42c7-9445-d2806d156403/fac575ac-7a41-484f-b7ac-875042de11f8?org_if_sml=1&force_format=original',
    },
    link2: {
      type: String,
      default: '網站種類',
    },
    link1: {
      type: String,
      default: '關於我們',
    },
  },
}
</script>

<style scoped>
.navbar3-container {
  width: 100%;
  display: flex;
  position: relative;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
</style>
