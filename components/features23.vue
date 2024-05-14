<template>
  <div class="features23-layout349 thq-section-padding">
    <div class="features23-max-width thq-section-max-width">
      <div class="features23-container">
        <h2 class="thq-heading-2">{{ heading1 }}</h2>
        <span class="features23-text01 thq-body-small">{{ content1 }}</span>
        <button class="thq-button-filled features23-button">
          <span class="thq-body-small">{{ action1 }}</span>
        </button>
      </div>
      <div class="thq-grid-3">
        <div class="features23-container2 thq-card">
          <img
            :alt="feature1ImageAlt"
            :src="feature1ImageSrc"
            class="features23-image thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature1Title }}</h2>
          <span class="features23-text03 thq-body-small">
            {{ feature1Description }}
          </span>
        </div>
        <div class="features23-container3 thq-card">
          <img
            :alt="feature2ImageAlt"
            :src="feature2ImageSrc"
            class="features23-image1 thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature2Title }}</h2>
          <span class="features23-text05 thq-body-small">
            {{ feature2Description }}
          </span>
        </div>
        <div class="features23-container4 thq-card">
          <img
            :alt="feature3ImageAlt"
            :src="feature3ImageSrc"
            class="features23-image2 thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature3Title }}</h2>
          <span class="features23-text07 thq-body-small">
            {{ feature3Description }}
          </span>
        </div>
        <div class="features23-container5 thq-card">
          <img
            :alt="feature4ImageAlt"
            :src="feature4ImageSrc"
            class="features23-image3 thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature4Title }}</h2>
          <span class="features23-text09 thq-body-small">
            {{ feature4Description }}
          </span>
        </div>
        <div class="features23-container6 thq-card">
          <img
            :alt="feature5ImageAlt"
            :src="feature5ImageSrc"
            class="features23-image4 thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature5Title }}</h2>
          <span class="features23-text11 thq-body-small">
            {{ feature5Description }}
          </span>
        </div>
        <div class="features23-container7 thq-card">
          <img
            :alt="feature6ImageAlt"
            :src="feature6ImageSrc"
            class="features23-image5 thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature6Title }}</h2>
          <span class="features23-text13 thq-body-small">
            {{ feature6Description }}
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features23',
  props: {
    feature4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1553877522-43269d4ea984?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU1Nnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature5Description: {
      type: String,
      default:
        'Experience convenient online doctor visits for medical consultations from the comfort of your home.',
    },
    feature4Title: {
      type: String,
      default: 'Web Development Services',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1493612276216-ee3925520721?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU1N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1546900703-cf06143d1239?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU1OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature1Description: {
      type: String,
      default:
        'We create custom website designs that align with your brand and business goals.',
    },
    feature3Description: {
      type: String,
      default:
        'We offer 24/7 customer support to address any queries or issues promptly.',
    },
    feature1Title: {
      type: String,
      default: 'Tailored Website Designs',
    },
    feature5ImageAlt: {
      type: String,
      default: 'Online Doctor Visits Image',
    },
    feature6Description: {
      type: String,
      default:
        'Stay updated with the latest news and offers by subscribing to our newsletter.',
    },
    feature3Title: {
      type: String,
      default: 'Round-the-Clock Customer Support',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Customer Support Image',
    },
    feature6Title: {
      type: String,
      default: 'Newsletter Subscription',
    },
    feature4Description: {
      type: String,
      default:
        'In addition to design, we provide comprehensive web development services to bring your vision to life.',
    },
    feature6ImageAlt: {
      type: String,
      default: 'Newsletter Subscription Image',
    },
    feature5Title: {
      type: String,
      default: 'Online Doctor Visits',
    },
    heading1: {
      type: String,
      default: 'Key Features',
    },
    feature6ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1576766125535-b04e15fd0273?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU1N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    content1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature2Description: {
      type: String,
      default:
        'Our team of developers ensures clean and efficient coding for optimal website performance.',
    },
    feature2Title: {
      type: String,
      default: 'High-Quality Coding',
    },
    feature4ImageAlt: {
      type: String,
      default: 'Web Development Services Image',
    },
    feature5ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1511988617509-a57c8a288659?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU1N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2ImageAlt: {
      type: String,
      default: 'High-Quality Coding Image',
    },
    action1: {
      type: String,
      default: 'Get Started',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1542435503-956c469947f6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU1Nnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Tailored Website Designs Image',
    },
  },
}
</script>

<style scoped>
.features23-layout349 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.features23-max-width {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.features23-container {
  gap: var(--dl-space-space-unit);
  display: flex;
  max-width: 600px;
  align-items: center;
  flex-direction: column;
}
.features23-text01 {
  text-align: center;
}
.features23-container2 {
  flex: 1;
  height: auto;
  display: flex;
  align-self: flex-start;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features23-image {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.features23-text03 {
  text-align: left;
}
.features23-container3 {
  flex: 1;
  height: auto;
  display: flex;
  align-self: flex-start;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features23-image1 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.features23-text05 {
  text-align: left;
}
.features23-container4 {
  flex: 1;
  height: auto;
  display: flex;
  align-self: flex-start;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features23-image2 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.features23-text07 {
  text-align: left;
}
.features23-container5 {
  flex: 1;
  height: auto;
  display: flex;
  align-self: flex-start;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features23-image3 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.features23-text09 {
  text-align: left;
}
.features23-container6 {
  flex: 1;
  height: auto;
  display: flex;
  align-self: flex-start;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features23-image4 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.features23-text11 {
  text-align: left;
}
.features23-container7 {
  flex: 1;
  height: auto;
  display: flex;
  align-self: flex-start;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features23-image5 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.features23-text13 {
  text-align: left;
}
@media(max-width: 991px) {
  .features23-max-width {
    flex-direction: column;
  }
  .features23-container {
    margin-bottom: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 767px) {
  .features23-container {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .features23-container2 {
    width: 100%;
  }
  .features23-container3 {
    width: 100%;
  }
  .features23-container4 {
    width: 100%;
  }
  .features23-container5 {
    width: 100%;
  }
  .features23-container6 {
    width: 100%;
  }
  .features23-container7 {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .features23-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .features23-button {
    width: 100%;
  }
}
</style>
