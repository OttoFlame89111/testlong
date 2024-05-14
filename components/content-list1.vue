<template>
  <div class="content-list1-container thq-section-padding">
    <div class="content-list1-max-width thq-section-max-width">
      <div class="content-list1-content thq-flex-column">
        <ul class="thq-flex-column">
          <li class="thq-flex-column list-item">
            <span id="prioacy" class="content-list1-heading1 thq-heading-2">
              {{ heading1 }}
            </span>
            <p class="thq-body-small">{{ content1 }}</p>
          </li>
          <li class="list-item">
            <h3 class="thq-heading-3">{{ heading2 }}</h3>
            <p class="content-list1-content2 thq-body-small">{{ content2 }}</p>
          </li>
          <li class="list-item">
            <h3 class="thq-heading-3">{{ heading3 }}</h3>
            <p class="thq-body-small">{{ content3 }}</p>
          </li>
          <li class="list-item">
            <h3 class="thq-heading-3">{{ heading4 }}</h3>
            <p class="content-list1-content4 thq-body-small">{{ content4 }}</p>
          </li>
          <li class="list-item">
            <h3 class="thq-heading-3">{{ heading5 }}</h3>
            <p class="content-list1-content5 thq-body-small">{{ content5 }}</p>
          </li>
          <li class="list-item">
            <h3 class="thq-heading-3">{{ heading6 }}</h3>
            <p class="content-list1-content6 thq-body-small">{{ content6 }}</p>
          </li>
        </ul>
        <span>{{ text }}</span>
        <span>{{ text1 }}</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentList1',
  props: {
    heading3: {
      type: String,
      default: '如何使用您的資訊',
    },
    text1: {
      type: String,
      default:
        '如果您有任何關於此隱私政策的問題，請通過以下方式聯絡我們： 地址：臺中市南區福平里美村路二段186號11樓之2',
    },
    content4: {
      type: String,
      default:
        '我們採取適當的技術和組織措施來保護您的個人資訊免受未經授權的訪問、使用或披露。',
    },
    content6: {
      type: String,
      default:
        '我們可能會不時更新此隱私政策。我們鼓勵您定期查看此政策，以了解我們如何保護您的資訊。',
    },
    content2: {
      type: String,
      default:
        '我們可能會收集以下類型的個人資訊：  姓名、聯絡資料（包括電子郵件地址和電話號碼） 技術資料，如IP地址、瀏覽器類型和版本、設備資訊 有關您如何使用我們的網站和服務的資訊',
    },
    content1: {
      type: String,
      default:
        '歡迎來到龍創資訊，藍創科技有限公司（以下簡稱“我們”）承諾保護和尊重您的隱私。本隱私權政策解釋了當您使用我們的網站服務時，我們如何收集、使用、保存、披露及保護您提供給我們的個人資訊。',
    },
    content3: {
      type: String,
      default:
        '我們使用收集的資訊來：  提供、維護和改進我們的服務 回應您的詢問或要求，提供客戶支持 進行市場分析和研究，以改善和定制我們的產品和服務 發送相關的營銷和宣傳資訊，前提是您已同意接收這類資訊 資訊的分享和披露除非獲得您的同意，我們不會與任何第三方分享您的個人資訊，除非：  根據法律要求或出於法律程序的需要 為了保護我們的權利或財產 在緊急情況下保護我們的客戶或公眾的個人安全',
    },
    heading5: {
      type: String,
      default: '您的權利',
    },
    heading1: {
      type: String,
      default: '隱私權政策',
    },
    heading6: {
      type: String,
      default: '變更',
    },
    content5: {
      type: String,
      default:
        '您有權要求訪問、更正或刪除您的個人資料。您也有權反對我們處理您的個人資料並要求限制處理。',
    },
    heading4: {
      type: String,
      default: '資料安全',
    },
    heading2: {
      type: String,
      default: '收集的資訊',
    },
    text: {
      type: String,
      default: '聯絡我們',
    },
  },
}
</script>

<style scoped>
.content-list1-container {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.content-list1-max-width {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
}
.content-list1-content {
  align-self: stretch;
  align-items: flex-start;
}
.content-list1-heading1 {
  align-self: flex-start;
}
.content-list1-content2 {
  width: 1048px;
}
.content-list1-content4 {
  width: 1069px;
  height: 23px;
}
.content-list1-content5 {
  width: 1071px;
  height: 63px;
}
.content-list1-content6 {
  width: 1063px;
  height: 63px;
}
</style>
