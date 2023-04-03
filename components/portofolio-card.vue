<template>
  <div class="portofolio-card-speaker-card" v-bind:class="rootClassName">
    <div class="portofolio-card-image-container">
      <img :alt="image_alt" :src="image_src" class="portofolio-card-image" />
      <div class="portofolio-card-see-project-container">
        <button class="button-secondary-white button button-md">
          See project
        </button>
      </div>
    </div>
    <span class="portofolio-card-first-name">{{ project_title }}</span>
  </div>
</template>

<script>
export default {
  name: 'PortofolioCard',
  props: {
    rootClassName: String,
    project_title: {
      type: String,
      default: 'Office Life Campaign - Boost your creativity',
    },
    image_alt: {
      type: String,
      default: 'image',
    },
    image_src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEwfHxwZW9wbGV8ZW58MHx8fHwxNjQzNzA1NTEx&ixlib=rb-1.2.1&w=300',
    },
  },
}
</script>

<style scoped>
.portofolio-card-speaker-card {
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.portofolio-card-image-container {
  width: 100%;
  height: 100%;
  display: flex;
  position: relative;
  min-width: 300px;
  max-height: 313px;
  min-height: 313px;
  align-items: flex-end;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
  justify-content: flex-end;
}
.portofolio-card-image {
  left: 0px;
  width: 100%;
  bottom: 0px;
  height: 100%;
  position: absolute;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.portofolio-card-see-project-container {
  flex: 1;
  width: 100%;
  cursor: pointer;
  display: flex;
  opacity: 0;
  z-index: 1;
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6));
  transition: 0.3s;
  align-items: center;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: row;
  justify-content: center;
}
.portofolio-card-see-project-container:hover {
  opacity: 1;
}
.portofolio-card-first-name {
  font-size: 18px;
  font-style: normal;
  font-weight: 700;
  line-height: 23px;
}






</style>
