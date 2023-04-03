<template>
  <header data-role="Header" class="navigation-header">
    <div class="navigation-max-width">
      <img :alt="image_alt" :src="image_src" />
      <div class="navigation-nav">
        <navigation-links
          rootClassName="navigation-links-root-class-name17"
        ></navigation-links>
        <button class="button-secondary button button-md">{{ button }}</button>
      </div>
      <div data-type="BurgerMenu" class="navigation-burger-menu">
        <svg viewBox="0 0 1024 1024" class="navigation-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-type="MobileMenu" class="mobile-menu">
        <div class="navigation-nav1">
          <div class="navigation-container">
            <img :alt="image_alt1" :src="image_src1" />
            <div data-type="CloseMobileMenu" class="navigation-close-mobile-menu">
              <svg viewBox="0 0 1024 1024" class="navigation-icon2">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <navigation-links
            rootClassName="navigation-links-root-class-name18"
          ></navigation-links>
          <button class="button-secondary button button-md">{{ button2 }}</button>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import NavigationLinks from './navigation-links'

export default {
  name: 'Navigation',
  props: {
    image_src: {
      type: String,
      default: '/playground_assets/logo1-1200w.png',
    },
    button: {
      type: String,
      default: 'Get in touch',
    },
    image_alt1: {
      type: String,
      default: 'image',
    },
    image_src1: {
      type: String,
      default: '/playground_assets/logo1-1200w.png',
    },
    button2: {
      type: String,
      default: 'Get in touch',
    },
    image_alt: {
      type: String,
      default: 'logo',
    },
  },
  components: {
    NavigationLinks,
  },
}
</script>

<style scoped>
.navigation-header {
  top: 0;
  width: 100%;
  display: flex;
  z-index: 100;
  position: fixed;
  align-items: center;
  justify-content: center;
  background-color: var(--dl-color-scheme-white);
}
.navigation-max-width {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
}
.navigation-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-burger-menu {
  display: none;
}
.navigation-icon {
  fill: var(--dl-color-scheme-darkblue);
  width: 24px;
  height: 24px;
  display: flex;
}
.navigation-nav1 {
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
}
.navigation-container {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.navigation-close-mobile-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
.navigation-icon2 {
  width: 24px;
  height: 24px;
}
@media(max-width: 991px) {
  .navigation-nav {
    display: none;
  }
  .navigation-burger-menu {
    display: flex;
  }
}
@media(max-width: 767px) {
  .navigation-max-width {
    padding: var(--dl-space-space-unit);
  }
}
</style>
