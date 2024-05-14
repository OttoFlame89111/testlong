<template>
  <div
    id="多元架站"
    class="features16-layout300 thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="features16-max-width thq-section-max-width">
      <div class="features16-section-title">
        <span class="features16-text thq-body-small">{{ slogan1 }}</span>
        <div class="features16-content">
          <h2 class="features16-text1 thq-heading-2">{{ heading1 }}</h2>
          <span class="features16-text2 thq-body-large">{{ content1 }}</span>
        </div>
      </div>
      <div class="features16-content1">
        <div class="features16-row thq-flex-row">
          <div class="features16-feature1">
            <img
              :alt="feature1ImageAlt"
              :src="feature1ImageSrc"
              class="thq-img-ratio-4-3"
            />
            <div class="features16-content2">
              <h3 class="features16-feature1-title thq-heading-3">
                {{ feature1Title }}
              </h3>
              <span class="features16-feature1-description thq-body-small">
                {{ feature1Description }}
              </span>
            </div>
          </div>
          <div class="features16-feature2">
            <img
              :alt="feature2ImageAlt"
              srcset="/template%204%20p-1400w.webp 1200w, /template%204%20p-tablet.webp 800w, /template%204%20p-mobile.webp 480w"
              sizes="(min-width: 992px) 1200px, (min-width: 768px) 800px, 480px"
              src="/template%204%20p-1400w.webp"
              class="thq-img-ratio-4-3"
            />
            <div class="features16-content3">
              <h3 class="features16-feature2-title thq-heading-3">
                {{ feature2Title }}
              </h3>
              <span class="features16-feature2-description thq-body-small">
                {{ feature2Description }}
              </span>
            </div>
          </div>
          <div class="features16-feature3">
            <img
              :alt="feature3ImageAlt"
              srcset="/c4b15b99-40d4-4167-8040-f6b784fcd4d6-1400w.webp 1200w, /c4b15b99-40d4-4167-8040-f6b784fcd4d6-tablet.webp 800w, /c4b15b99-40d4-4167-8040-f6b784fcd4d6-mobile.webp 480w"
              sizes="(min-width: 992px) 1200px, (min-width: 768px) 800px, 480px"
              src="/c4b15b99-40d4-4167-8040-f6b784fcd4d6-1400w.webp"
              class="thq-img-ratio-4-3"
            />
            <div class="features16-content4">
              <h3 class="features16-feature3-title thq-heading-3">
                {{ feature3Title }}
              </h3>
              <span class="features16-feature3-description thq-body-small">
                {{ feature3Description }}
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features16',
  props: {
    slogan1: {
      type: String,
      default: 'Innovate with Purpose',
    },
    feature3Title: {
      type: String,
      default: '一頁式網站',
    },
    feature2Description: {
      type: String,
      default:
        '一個完整的電子商務平台，讓消費者能夠方便地瀏覽產品、放入購物車並進行結帳，支持多種支付方式。',
    },
    feature2Title: {
      type: String,
      default: '購物網站',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Custom Website Design Image',
    },
    feature1Description: {
      type: String,
      default:
        '專為展示企業品牌和價值設計的網站，透過視覺和內容傳達企業的專業形象和業務範疇。',
    },
    rootClassName: String,
    content1: {
      type: String,
      default: 'Innovate with Purpose',
    },
    feature2ImageAlt: {
      type: String,
      default: 'Dedicated Development Team Image',
    },
    feature1Title: {
      type: String,
      default: '形象網站',
    },
    feature1ImageSrc: {
      type: String,
      default: '/screenshot%20from%202024-05-13%2013-29-33-1400w.webp',
    },
    feature3ImageSrc: {
      type: String,
      default: '00feb57f-3007-4650-8548-fe58a4f42d62',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1602265585142-6b221b9b2c24?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NTM2Nnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3Description: {
      type: String,
      default:
        '所有內容集中在單一頁面上，透過滾動或點擊導航逐段展開信息，適合展示簡潔的企業資訊或活動細節。',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Customer Support Image',
    },
    heading1: {
      type: String,
      default: '多元網站架設',
    },
  },
}
</script>

<style scoped>
.features16-layout300 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.features16-max-width {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.features16-section-title {
  gap: 16px;
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.features16-text {
  text-align: center;
}
.features16-content {
  gap: 24px;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.features16-text1 {
  color: #ffffff;
  text-align: center;
}
.features16-text2 {
  color: #ffffff;
  text-align: center;
}
.features16-content1 {
  gap: 48px;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.features16-row {
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
  justify-content: center;
}
.features16-feature1 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features16-content2 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.features16-feature1-title {
  color: #ffffff;
  text-align: center;
}
.features16-feature1-description {
  color: #ffffff;
}
.features16-feature2 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features16-content3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.features16-feature2-title {
  color: #ffffff;
}
.features16-feature2-description {
  color: #ffffff;
}
.features16-feature3 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.features16-content4 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.features16-feature3-title {
  color: #ffffff;
}
.features16-feature3-description {
  color: #ffffff;
}

@media(max-width: 991px) {
  .features16-section-title {
    width: 100%;
  }
}
@media(max-width: 767px) {
  .features16-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .features16-section-title {
    width: auto;
  }
  .features16-text1 {
    text-align: center;
  }
  .features16-feature2 {
    width: auto;
  }
  .features16-feature3 {
    width: auto;
  }
}
</style>
