<template>
  <div class="services-card">
    <div class="services-card-container">
      <img :alt="image_alt" :src="image_src" class="services-card-image" />
    </div>
    <span class="services-card-text">{{ text }}</span>
    <span class="services-card-text1">{{ text1 }}</span>
    <span class="services-card-text2">{{ text2 }}</span>
  </div>
</template>

<script>
export default {
  name: 'ServicesCard',
  props: {
    image_alt: {
      type: String,
      default: 'image',
    },
    image_src: {
      type: String,
      default: '/playground_assets/website-200h.png',
    },
    text: {
      type: String,
      default: 'Website design',
    },
    text1: {
      type: String,
      default:
        'Create your ubest unique App development, crafted for your business needs.',
    },
    text2: {
      type: String,
      default: 'Learn more',
    },
  },
}
</script>

<style scoped>
.services-card-container {
  width: 56px;
  height: 56px;
  display: flex;
  align-items: center;
  border-radius: var(--dl-radius-radius-radius4);
  margin-bottom: var(--dl-space-space-twounits);
  justify-content: center;
  background-color: rgba(182, 71, 47, 0.1);
}
.services-card-image {
  width: 24px;
  height: 24px;
  object-fit: contain;
}
.services-card-text {
  font-size: 24px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.services-card-text1 {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.services-card-text2 {
  cursor: pointer;
  text-decoration: underline;
}
</style>
