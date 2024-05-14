<template>
  <div class="navbar31-container">
    <header data-thq="thq-navbar" class="navbar31-navbar-interactive">
      <img
        :alt="logoAlt"
        :src="logoSrc"
        loading="eager"
        class="navbar31-image1"
      />
      <div data-thq="thq-navbar-nav" class="navbar31-desktop-menu">
        <nav class="navbar31-links">
          <a href="#aboutus" class="navbar31-link1 thq-body-small thq-link">
            {{ link1 }}
          </a>
          <a href="#多元架站" class="navbar31-link2 thq-body-small thq-link">
            {{ link2 }}
          </a>
          <a href="#price" class="navbar31-link3 thq-body-small thq-link">
            {{ link3 }}
          </a>
          <a href="#q a" class="navbar31-link4 thq-body-small thq-link">
            {{ link4 }}
          </a>
          <a
            href="https://line.me/ti/p/@768wbdzv"
            target="_blank"
            rel="noreferrer noopener"
            class="navbar31-link5 thq-body-small thq-link"
          >
            {{ link5 }}
          </a>
        </nav>
      </div>
      <div data-thq="thq-burger-menu" class="navbar31-burger-menu">
        <svg viewBox="0 0 1024 1024" class="navbar31-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-thq="thq-mobile-menu" class="navbar31-mobile-menu">
        <div class="navbar31-nav">
          <div class="navbar31-top">
            <img :alt="logoAlt" :src="logoSrc" class="navbar31-logo" />
            <div data-thq="thq-close-menu" class="navbar31-close-menu">
              <svg viewBox="0 0 1024 1024" class="navbar31-icon2">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <nav class="navbar31-links1">
            <a href="#aboutus" class="navbar31-link11 thq-body-small thq-link">
              {{ link1 }}
            </a>
            <a href="#多元架站" class="navbar31-link21 thq-body-small thq-link">
              {{ link2 }}
            </a>
            <a href="#price" class="navbar31-link31 thq-body-small thq-link">
              {{ link3 }}
            </a>
            <a href="#q a" class="navbar31-link41 thq-body-small thq-link">
              {{ link4 }}
            </a>
            <a href="#text me" class="navbar31-link51 thq-body-small thq-link">
              {{ link5 }}
            </a>
          </nav>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Navbar31',
  props: {
    link3: {
      type: String,
      default: '價位',
    },
    imageSrc: {
      type: String,
      default: 'c4f8f95d-497f-4c3e-bbca-6108d4be91c9',
    },
    link2: {
      type: String,
      default: '網站總類',
    },
    link1: {
      type: String,
      default: '關於我們',
    },
    logoSrc: {
      type: String,
      default:
        '/screenshot_from_2024-05-09_16-09-31-removebg-preview-1500h.webp',
    },
    logoAlt: {
      type: String,
      default: 'logo',
    },
    link4: {
      type: String,
      default: 'Q & A',
    },
    imageAlt: {
      type: String,
      default: 'image',
    },
    link5: {
      type: String,
      default: '聯絡我們',
    },
  },
}
</script>

<style scoped>
.navbar31-container {
  width: 100%;
  display: flex;
  position: relative;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
.navbar31-navbar-interactive {
  width: 100%;
  display: flex;
  max-width: idth;
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
  background-color: #000000;
}
.navbar31-image1 {
  width: 314px;
  height: 260px;
  margin-left: var(--dl-space-space-halfunit);
}
.navbar31-desktop-menu {
  flex: 1;
  display: flex;
  justify-content: space-between;
}
.navbar31-links {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.navbar31-link1 {
  color: #ffffff;
  font-size: 20px;
  font-style: normal;
  font-family: "Inter";
  font-weight: 600;
  text-decoration: none;
  background-color: #000000;
}
.navbar31-link2 {
  color: #ffffff;
  font-size: 20px;
  text-decoration: none;
}
.navbar31-link3 {
  color: #ffffff;
  font-size: 20px;
  text-decoration: none;
}
.navbar31-link4 {
  color: #ffffff;
  font-size: 22px;
  text-decoration: none;
}
.navbar31-link5 {
  color: #ffffff;
  font-size: 20px;
  text-decoration: none;
}
.navbar31-burger-menu {
  display: none;
}
.navbar31-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.navbar31-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: flex;
  padding: var(--dl-space-space-twounits);
  z-index: 100;
  position: absolute;
  transform: translateX(-100%);
  transition: 0.5s;
  flex-direction: column;
  justify-content: space-between;
  background-color: var(--dl-color-theme-neutral-light);
}
.navbar31-nav {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.navbar31-top {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.navbar31-logo {
  height: 3rem;
}
.navbar31-close-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
.navbar31-icon2 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.navbar31-links1 {
  gap: var(--dl-space-space-unit);
  flex: 0 0 auto;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
.navbar31-link11 {
  text-decoration: none;
}
.navbar31-link21 {
  text-decoration: none;
}
.navbar31-link31 {
  text-decoration: none;
}
.navbar31-link41 {
  text-decoration: none;
}
.navbar31-link51 {
  text-decoration: none;
}
@media(max-width: 767px) {
  .navbar31-navbar-interactive {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
    background-color: #000000;
  }
  .navbar31-image1 {
    width: 130px;
    height: 100px;
  }
  .navbar31-desktop-menu {
    display: none;
  }
  .navbar31-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .navbar31-icon {
    fill: #ffffff;
  }
  .navbar31-logo {
    width: 213px;
    height: 156px;
  }
}
@media(max-width: 479px) {
  .navbar31-navbar-interactive {
    padding: var(--dl-space-space-unit);
  }
  .navbar31-image1 {
    width: 94px;
    height: 86px;
  }
  .navbar31-mobile-menu {
    padding: var(--dl-space-space-unit);
  }
}
</style>
