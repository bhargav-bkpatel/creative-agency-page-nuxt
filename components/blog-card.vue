<template>
  <div class="blog-card-blog-card" v-bind:class="rootClassName">
    <img :alt="image_alt" :src="image_src" class="blog-card-image" />
    <div class="blog-card-container">
      <button class="blog-card-button button-secondary button">
        {{ button }}
      </button>
      <span class="blog-card-text">{{ text1 }}</span>
    </div>
    <span class="blog-card-text1">
      <span>
        Excepteur sint occaecat cupidatat non proident, sunt
        <span v-html="rawybyq"></span>
      </span>
      <span>in culpa qui and.</span>
    </span>
    <span class="blog-card-text4">{{ text }}</span>
  </div>
</template>

<script>
export default {
  name: 'BlogCard',
  props: {
    button: {
      type: String,
      default: 'Web Design',
    },
    image_alt: {
      type: String,
      default: 'image',
    },
    text1: {
      type: String,
      default: 'Dec 8, 2022',
    },
    image_src: {
      type: String,
      default: '/playground_assets/rectangle%2099-1500w.png',
    },
    rootClassName: String,
    text: {
      type: String,
      default: 'Learn more',
    },
  },

  data() {
    return {
      rawybyq: ' ',
    }
  },
}
</script>

<style scoped>
.blog-card-blog-card {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  max-width: 300px;
  align-items: flex-start;
  flex-direction: column;
}
.blog-card-image {
  width: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
  margin-bottom: var(--dl-space-space-halfunit);
}
.blog-card-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
  flex-direction: row;
  justify-content: space-between;
}
.blog-card-button {
  font-size: 12px;
  text-transform: uppercase;
}
.blog-card-text {
  font-size: 12px;
  font-style: normal;
  font-weight: 700;
}
.blog-card-text1 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 26px;
  margin-bottom: var(--dl-space-space-unit);
}
.blog-card-text4 {
  text-decoration: underline;
}


@media(max-width: 991px) {
  .blog-card-blog-card {
    max-width: 550px;
  }
}
@media(max-width: 767px) {
  .blog-card-blog-card {
    max-width: 450px;
  }
  .blog-card-root-class-name {
    margin-bottom: var(--dl-space-space-twounits);
  }
  .blog-card-root-class-name1 {
    margin-bottom: var(--dl-space-space-twounits);
  }
}
@media(max-width: 479px) {
  .blog-card-blog-card {
    max-width: 350px;
  }
}
</style>
