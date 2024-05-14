<template>
  <div class="features211-layout349 thq-section-padding">
    <div class="features211-max-width thq-grid-4 thq-section-max-width">
      <div class="features211-container thq-card thq-flex-column">
        <img
          :alt="feature1ImageAlt"
          :src="feature1ImageSrc"
          class="features211-image thq-img-ratio-1-1"
        />
        <h2 class="thq-heading-2">{{ feature1Title }}</h2>
        <span class="features211-text1 thq-body-small">
          {{ feature1Description }}
        </span>
      </div>
      <div class="features211-container1 thq-card thq-flex-column">
        <img
          :alt="feature2ImageAlt"
          :src="feature2ImageSrc"
          class="features211-image1 thq-img-ratio-1-1"
        />
        <h2 class="features211-text2 thq-heading-2">{{ feature2Title }}</h2>
        <span class="features211-text3 thq-body-small">
          {{ feature2Description }}
        </span>
      </div>
      <div class="features211-container2 thq-card thq-flex-column">
        <img
          :alt="feature3ImageAlt"
          :src="feature3ImageSrc"
          class="features211-image2 thq-img-ratio-1-1"
        />
        <h2 class="features211-text4 thq-heading-2">{{ feature3Title }}</h2>
        <span class="features211-text5 thq-body-small">
          {{ feature3Description }}
        </span>
      </div>
      <div class="features211-container3 thq-card thq-flex-column">
        <img
          :alt="feature4ImageAlt"
          :src="feature4ImageSrc"
          class="features211-image3 thq-img-ratio-1-1"
        />
        <h2 class="features211-text6 thq-heading-2">{{ feature4Title }}</h2>
        <span class="features211-text7 thq-body-small">
          {{ feature4Description }}
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features211',
  props: {
    feature2ImageAlt: {
      type: String,
      default: 'seo',
    },
    feature2Description: {
      type: String,
      default:
        '涉及創建視覺吸引且使用者友好的網頁。這包括布局設計、色彩選擇、字型運用以及創造一個流暢的用戶體驗(UX)和用戶界面(UI)。',
    },
    feature3Description: {
      type: String,
      default:
        '結合不同的行銷策略和渠道，如數位行銷、社群媒體行銷、電子郵件行銷、內容行銷等，以達到更廣泛的市場覆蓋和吸引不同的顧客群。',
    },
    feature2Title: {
      type: String,
      default: '網站設計',
    },
    feature2ImageSrc: {
      type: String,
      default:
        '/%C3%A7%C2%B6%C2%B2%C3%A7%C2%AB%C2%99%C3%A7%C2%B4%C2%A0%C3%A6%C2%9D%C2%90-1400w.webp',
    },
    feature1Description: {
      type: String,
      default:
        '透過優化網站的結構和內容，提升網站在搜尋引擎中的排名，以吸引更多的自然流量。這包括關鍵字研究、內容創作、技術優化和外部連結建設。',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Online Doctor Visits Image',
    },
    feature1Title: {
      type: String,
      default: 'SEO',
    },
    feature4Description: {
      type: String,
      default:
        '涵蓋從桌面軟體、移動應用到企業解決方案的開發。這包括需求分析、系統設計、程式編寫、測試以及維護，旨在提供符合特定業務需求的軟體解決方案。',
    },
    feature3ImageSrc: {
      type: String,
      default: '/%C3%A8%C2%A1%C2%8C%C3%A9%C2%8A%C2%B7%201-1400w.webp',
    },
    feature4Title: {
      type: String,
      default: '軟體開發',
    },
    feature3Title: {
      type: String,
      default: '多元行銷',
    },
    feature4ImageAlt: {
      type: String,
      default: 'Round-the-Clock Support Image',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Website Design Image',
    },
    feature4ImageSrc: {
      type: String,
      default: '/0d289ae0-7b74-449c-8b4f-ea19cadf56ce-1400w.webp',
    },
    feature1ImageSrc: {
      type: String,
      default: '/90a276ed-4d37-4466-90ac-d5f9a0437590-1400w.webp',
    },
  },
}
</script>

<style scoped>
.features211-layout349 {
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.features211-max-width {
  display: flex;
  align-items: center;
}
.features211-container {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features211-image {
  width: 150px;
  height: 104px;
  object-fit: cover;
}
.features211-text1 {
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.features211-container1 {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features211-image1 {
  width: 175px;
  height: 112px;
  object-fit: cover;
}
.features211-text2 {
  font-family: "Inter";
}
.features211-text3 {
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.features211-container2 {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features211-image2 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
.features211-text4 {
  font-family: "Inter";
}
.features211-text5 {
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.features211-container3 {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features211-image3 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
.features211-text6 {
  font-family: "Inter";
}
.features211-text7 {
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
@media(max-width: 991px) {
  .features211-max-width {
    gap: var(--dl-space-space-twounits);
    flex-direction: column-reverse;
  }
}
@media(max-width: 767px) {
  .features211-container {
    width: 100%;
  }
  .features211-container1 {
    width: 100%;
  }
  .features211-container2 {
    width: 100%;
  }
  .features211-container3 {
    width: 100%;
  }
}
</style>
