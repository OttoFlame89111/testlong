<template>
  <div class="privacy-policy-container">
    <nuxt-link to="/" class="privacy-policy-navlink">
      <svg viewBox="0 0 1024 1024" class="privacy-policy-icon">
        <path
          d="M225.835 286.165l225.835 225.835-225.835 225.835c-16.683 16.683-16.683 43.691 0 60.331s43.691 16.683 60.331 0l225.835-225.835 225.835 225.835c16.683 16.683 43.691 16.683 60.331 0s16.683-43.691 0-60.331l-225.835-225.835 225.835-225.835c16.683-16.683 16.683-43.691 0-60.331s-43.691-16.683-60.331 0l-225.835 225.835-225.835-225.835c-16.683-16.683-43.691-16.683-60.331 0s-16.683 43.691 0 60.331z"
        ></path>
      </svg>
    </nuxt-link>
    <div class="privacy-policy-cta2"></div>
    <div class="privacy-policy-contentlist3"><content-list1></content-list1></div>
  </div>
</template>

<script>
import ContentList1 from '../components/content-list1'

export default {
  name: 'PrivacyPolicy',
  props: {},
  components: {
    ContentList1,
  },
  head: {
    title: 'Privacy-Policy - 龍創資訊 | 客製化 網站和軟體開發專家 WordPress',
    meta: [
      {
        name: 'description',
        content:
          '專注於提供客製化的 WordPress 購物網站和企業形象網站開發，龍創資訊擁有專業團隊，以實現您的數位轉型需求。立即聯絡了解更多！',
      },
      {
        property: 'og:title',
        content:
          'Privacy-Policy - 龍創資訊 | 客製化 網站和軟體開發專家 WordPress',
      },
      {
        property: 'og:description',
        content:
          '專注於提供客製化的 WordPress 購物網站和企業形象網站開發，龍創資訊擁有專業團隊，以實現您的數位轉型需求。立即聯絡了解更多！',
      },
    ],
  },
}
</script>

<style scoped>
.privacy-policy-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.privacy-policy-navlink {
  display: contents;
}
.privacy-policy-icon {
  width: 80px;
  height: 80px;
  align-self: flex-end;
  text-decoration: none;
}
.privacy-policy-cta2 {
  flex: 0 0 auto;
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.privacy-policy-contentlist3 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
