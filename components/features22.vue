<template>
  <div class="features22-layout349 thq-section-padding">
    <div class="features22-max-width thq-section-max-width">
      <div class="features22-container">
        <h2 class="thq-heading-2">{{ heading1 }}</h2>
        <span class="features22-text01 thq-body-small">{{ content1 }}</span>
      </div>
      <div class="features22-container1 thq-grid-4">
        <div class="features22-card thq-card">
          <img
            :alt="feature1ImageAlt"
            :src="feature1ImageSrc"
            class="features22-image thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature1Title }}</h2>
          <span class="features22-text03 thq-body-small">
            {{ feature1Description }}
          </span>
        </div>
        <div class="features22-card1 thq-card">
          <img
            :alt="feature2ImageAlt"
            :src="feature2ImageSrc"
            class="features22-image1 thq-img-round"
          />
          <h2 class="thq-heading-2">{{ feature2Title }}</h2>
          <span class="features22-text05 thq-body-small">
            {{ feature2Description }}
          </span>
        </div>
        <div class="features22-card2 thq-card">
          <img
            :alt="feature3ImageAlt"
            :src="feature3ImageSrc"
            class="features22-image2 thq-img-round"
          />
          <h1 class="thq-heading-2">{{ feature3Title }}</h1>
          <span class="features22-text07 thq-body-small">
            {{ feature3Description }}
          </span>
        </div>
        <div class="features22-card3 thq-card">
          <img
            :alt="feature4ImageAlt"
            :src="feature4ImageSrc"
            class="features22-image3 thq-img-round"
          />
          <h1 class="thq-heading-2">{{ feature4Title }}</h1>
          <span class="features22-text09 thq-body-small">
            {{ feature4Description }}
          </span>
        </div>
        <div class="features22-card4 thq-card">
          <img
            :alt="feature5ImageAlt"
            :src="feature5ImageSrc"
            class="features22-image4 thq-img-round"
          />
          <h1 class="thq-heading-2">{{ feature5Title }}</h1>
          <span class="features22-text11 thq-body-small">
            {{ feature5Description }}
          </span>
        </div>
        <div class="features22-card5 thq-card">
          <img
            :alt="feature6ImageAlt"
            :src="feature6ImageSrc"
            class="features22-image5 thq-img-round"
          />
          <h1 class="thq-heading-2">{{ feature6Title }}</h1>
          <span class="features22-text13 thq-body-small">
            {{ feature6Description }}
          </span>
        </div>
        <div class="features22-card6 thq-card">
          <img
            :alt="feature7ImageAlt"
            :src="feature7ImageSrc"
            class="features22-image6 thq-img-round"
          />
          <h1 class="thq-heading-2">{{ feature7Title }}</h1>
          <span class="features22-text15 thq-body-small">
            {{ feature7Description }}
          </span>
        </div>
        <div class="features22-card7 thq-card">
          <img
            :alt="feature8ImageAlt"
            :src="feature8ImageSrc"
            class="features22-image7 thq-img-round"
          />
          <h1 class="thq-heading-2">{{ feature8Title }}</h1>
          <span class="features22-text17 thq-body-small">
            {{ feature8Description }}
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features22',
  props: {
    feature2Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature7Title: {
      type: String,
      default: 'Heading',
    },
    feature5Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature8ImageAlt: {
      type: String,
      default: 'image',
    },
    feature6ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    heading1: {
      type: String,
      default: 'Discover',
    },
    feature3ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    feature7ImageAlt: {
      type: String,
      default: 'image',
    },
    feature2ImageAlt: {
      type: String,
      default: 'image',
    },
    feature8Title: {
      type: String,
      default: 'Heading',
    },
    feature7Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature4Title: {
      type: String,
      default: 'Heading',
    },
    feature8ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    content1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature3Title: {
      type: String,
      default: 'Heading',
    },
    feature1Title: {
      type: String,
      default: 'Heading',
    },
    feature4ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    feature8Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature5Title: {
      type: String,
      default: 'Heading',
    },
    feature2ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    feature6Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature7ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    feature4Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature5ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    feature6ImageAlt: {
      type: String,
      default: 'image',
    },
    feature1ImageAlt: {
      type: String,
      default: 'image',
    },
    feature1ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    feature3Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature4ImageAlt: {
      type: String,
      default: 'image',
    },
    feature1Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature6Title: {
      type: String,
      default: 'Heading',
    },
    feature2Title: {
      type: String,
      default: 'Heading',
    },
    feature3ImageAlt: {
      type: String,
      default: 'image',
    },
    feature5ImageAlt: {
      type: String,
      default: 'image',
    },
  },
}
</script>

<style scoped>
.features22-layout349 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.features22-max-width {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.features22-container {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  max-width: 600px;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.features22-text01 {
  text-align: center;
}
.features22-container1 {
  width: 100%;
}
.features22-card {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text03 {
  text-align: center;
}
.features22-card1 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image1 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text05 {
  text-align: center;
}
.features22-card2 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image2 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text07 {
  text-align: center;
}
.features22-card3 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image3 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text09 {
  text-align: center;
}
.features22-card4 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image4 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text11 {
  text-align: center;
}
.features22-card5 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image5 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text13 {
  text-align: center;
}
.features22-card6 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image6 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text15 {
  text-align: center;
}
.features22-card7 {
  width: 100%;
  display: flex;
  box-shadow: 2px 2px 4px 0px #d4d4d4;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
}
.features22-image7 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
}
.features22-text17 {
  text-align: center;
}
@media(max-width: 991px) {
  .features22-max-width {
    flex-direction: column;
  }
  .features22-container {
    margin-bottom: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 767px) {
  .features22-container {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .features22-card {
    width: 100%;
  }
  .features22-card1 {
    width: 100%;
  }
  .features22-card2 {
    width: 100%;
  }
  .features22-card3 {
    width: 100%;
  }
  .features22-card4 {
    width: 100%;
  }
  .features22-card5 {
    width: 100%;
  }
  .features22-card6 {
    width: 100%;
  }
  .features22-card7 {
    width: 100%;
  }
}
</style>
