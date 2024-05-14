<template>
  <div class="features21-layout349 thq-section-padding">
    <div class="features21-max-width thq-grid-4 thq-section-max-width">
      <div class="features21-container thq-card thq-flex-column">
        <img
          :alt="feature1ImageAlt"
          :src="feature1ImageSrc"
          class="features21-image thq-img-ratio-1-1"
        />
        <h2 class="thq-heading-2">{{ feature1Title }}</h2>
        <span class="features21-text1 thq-body-small">
          {{ feature1Description }}
        </span>
      </div>
      <div class="features21-container1 thq-card thq-flex-column">
        <img
          :alt="feature2ImageAlt"
          :src="feature2ImageSrc"
          class="features21-image1 thq-img-ratio-1-1"
        />
        <h2 class="thq-heading-2">{{ feature2Title }}</h2>
        <span class="features21-text3 thq-body-small">
          {{ feature2Description }}
        </span>
      </div>
      <div class="features21-container2 thq-card thq-flex-column">
        <img
          :alt="feature3ImageAlt"
          :src="feature3ImageSrc"
          class="features21-image2 thq-img-ratio-1-1"
        />
        <h2 class="thq-heading-2">{{ feature3Title }}</h2>
        <span class="features21-text5 thq-body-small">
          {{ feature3Description }}
        </span>
      </div>
      <div class="features21-container3 thq-card thq-flex-column">
        <img
          :alt="feature4ImageAlt"
          :src="feature4ImageSrc"
          class="features21-image3 thq-img-ratio-1-1"
        />
        <h2 class="thq-heading-2">{{ feature4Title }}</h2>
        <span class="features21-text7 thq-body-small">
          {{ feature4Description }}
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features21',
  props: {
    feature3ImageAlt: {
      type: String,
      default: 'Round-the-Clock Customer Support Image',
    },
    feature2Description: {
      type: String,
      default:
        'We ensure top-notch coding standards for robust and efficient websites.',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Tailored Website Designs Image',
    },
    feature4Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature2ImageAlt: {
      type: String,
      default: 'High-Quality Coding Image',
    },
    feature1Description: {
      type: String,
      default:
        'Our team creates custom website designs to suit your brand and business needs.',
    },
    feature4ImageAlt: {
      type: String,
      default: 'image',
    },
    feature2Title: {
      type: String,
      default: 'High-Quality Coding',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1522202176988-66273c2fd55f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU5Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3Description: {
      type: String,
      default:
        'Our dedicated support team is available 24/7 to assist you with any queries or issues.',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1573164574001-518958d9baa2?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU5M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3Title: {
      type: String,
      default: 'Round-the-Clock Customer Support',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1707929591972-43d4060c3377?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU5Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1629752187687-3d3c7ea3a21b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxNTE0NzU5M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature1Title: {
      type: String,
      default: 'Tailored Website Designs',
    },
    feature4Title: {
      type: String,
      default: 'Heading',
    },
  },
}
</script>

<style scoped>
.features21-layout349 {
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.features21-max-width {
  display: flex;
  align-items: center;
}
.features21-container {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features21-image {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
.features21-text1 {
  text-align: center;
}
.features21-container1 {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features21-image1 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
.features21-text3 {
  text-align: center;
}
.features21-container2 {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent1);
}
.features21-image2 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
.features21-text5 {
  text-align: center;
}
.features21-container3 {
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-accent2);
}
.features21-image3 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
.features21-text7 {
  text-align: center;
}
@media(max-width: 991px) {
  .features21-max-width {
    gap: var(--dl-space-space-twounits);
    flex-direction: column-reverse;
  }
}
@media(max-width: 767px) {
  .features21-container {
    width: 100%;
  }
  .features21-container1 {
    width: 100%;
  }
  .features21-container2 {
    width: 100%;
  }
  .features21-container3 {
    width: 100%;
  }
}
</style>
