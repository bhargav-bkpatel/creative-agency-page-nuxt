<template>
  <div class="home-container">
    <app-navigation></app-navigation>
    <main class="home-main">
      <div class="home-hero section-container">
        <div class="home-max-width max-content-container">
          <div class="home-heading-container">
            <h1 class="home-text heading1">
              <span>We are a creative agency based</span>
              <br />
              <span>in Massachusetts</span>
            </h1>
            <span class="home-text03">
              <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod
              </span>
              <br />
              <span>tempor incididunt ut labore et dolore magna aliqua.</span>
            </span>
            <button class="home-primary button-primary button-lg button">
              Get in touch with us
            </button>
          </div>
          <div class="home-gallery">
            <div class="home-container1">
              <img
                alt="image"
                src="/playground_assets/rectangle%2095-1000w.png"
                class="home-image"
              />
            </div>
            <div class="home-container2">
              <img
                alt="image"
                src="/playground_assets/rectangle%2095%20%5B1%5D-1000w.png"
                class="home-image1"
              />
              <img
                alt="image"
                src="/playground_assets/rectangle%2095%20%5B2%5D-1000w.png"
                class="home-image2"
              />
            </div>
            <div class="home-container3">
              <img
                alt="image"
                src="/playground_assets/rectangle%2095%20%5B3%5D-1000w.png"
                class="home-image3"
              />
              <div class="home-container4">
                <img
                  alt="image"
                  src="/playground_assets/rectangle%2095%20%5B4%5D-1000w.png"
                  class="home-image4"
                />
                <img
                  alt="image"
                  src="/playground_assets/rectangle%2095%20%5B5%5D-1000w.png"
                  class="home-image5"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="home-services section-container">
        <div class="home-max-width1 max-content-container">
          <div class="home-heading-container1">
            <div class="home-text-container">
              <span class="home-text07">our services</span>
              <h2 class="heading2">
                <span>
                  We provide a wide range of
                  <span v-html="raw1qvr"></span>
                </span>
                <br />
                <span>creative solutions</span>
              </h2>
            </div>
            <div class="home-controls">
              <button class="control-btn">
                <svg viewBox="0 0 1024 1024" class="home-icon">
                  <path
                    d="M402.746 877.254l-320-320c-24.994-24.992-24.994-65.516 0-90.51l320-320c24.994-24.992 65.516-24.992 90.51 0 24.994 24.994 24.994 65.516 0 90.51l-210.746 210.746h613.49c35.346 0 64 28.654 64 64s-28.654 64-64 64h-613.49l210.746 210.746c12.496 12.496 18.744 28.876 18.744 45.254s-6.248 32.758-18.744 45.254c-24.994 24.994-65.516 24.994-90.51 0z"
                  ></path>
                </svg>
              </button>
              <button class="control-btn">
                <svg viewBox="0 0 1024 1024" class="home-icon02">
                  <path
                    d="M621.254 877.254l320-320c24.994-24.992 24.994-65.516 0-90.51l-320-320c-24.994-24.992-65.516-24.992-90.51 0-24.994 24.994-24.994 65.516 0 90.51l210.746 210.746h-613.49c-35.346 0-64 28.654-64 64s28.654 64 64 64h613.49l-210.746 210.746c-12.496 12.496-18.744 28.876-18.744 45.254s6.248 32.758 18.744 45.254c24.994 24.994 65.516 24.994 90.51 0z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
          <div class="home-cards-container">
            <services-card></services-card>
            <services-card
              text="Copy-writting"
              image_src="/playground_assets/file-document-200w.png"
            ></services-card>
            <services-card
              text="Product Design"
              image_src="/playground_assets/dice-5-200h.png"
            ></services-card>
          </div>
        </div>
      </div>
      <div class="section-container">
        <div class="home-max-width2 max-content-container">
          <div class="home-text-container1">
            <span class="home-text12">our work</span>
            <h2 class="home-text13 heading2">
              <span>Explore our portfolio</span>
            </h2>
            <span class="home-text15">
              <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut
                <span v-html="rawxyn1"></span>
              </span>
              <br />
              <span>
                labore et dolore magna aliqua. Ut enim ad minim veniam, quis
                nostrud exercitation.
              </span>
            </span>
            <button class="button-secondary button-lg button">
              See all projects
            </button>
          </div>
          <div class="home-tab-selector-header">
            <span class="home-text19 tab-selector-btn">Advertising</span>
            <span class="home-text20 tab-selector-btn">Social Media</span>
            <span class="home-text21 tab-selector-btn">Branding</span>
            <span class="home-text22 tab-selector-btn">UI / UX</span>
            <span class="home-text23 tab-selector-btn">Packaging</span>
            <span class="tab-selector-btn">Product Design</span>
          </div>
          <div class="home-tab-selector-cards-container">
            <portofolio-card
              image_src="/playground_assets/unsplash_qj15unotnh0-400h.png"
              rootClassName="portofolio-card-root-class-name"
            ></portofolio-card>
            <portofolio-card
              image_src="/playground_assets/unsplash_wwqrpsnbpq4-400h.png"
              project_title="A brand-new advertising idea"
              rootClassName="portofolio-card-root-class-name5"
            ></portofolio-card>
            <portofolio-card
              image_src="https://images.unsplash.com/photo-1622483767028-3f66f32aef97?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEzfHxjb2NhJTIwY29sYXxlbnwwfHx8fDE2NDY5MjYyNTM&amp;ixlib=rb-1.2.1&amp;h=400"
              project_title="Coca-Cola Summer Concept Campaign - 2021"
              rootClassName="portofolio-card-root-class-name4"
            ></portofolio-card>
            <portofolio-card
              image_src="https://images.unsplash.com/photo-1519420573924-65fcd45245f8?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDJ8fG51dGVsbGF8ZW58MHx8fHwxNjQ2OTI2MTky&amp;ixlib=rb-1.2.1&amp;h=400"
              project_title="Ad Campaign - I love you as much as I love Nutella"
              rootClassName="portofolio-card-root-class-name3"
            ></portofolio-card>
            <portofolio-card
              image_src="https://images.unsplash.com/photo-1567103472667-6898f3a79cf2?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDd8fGNvY2ElMjBjb2xhfGVufDB8fHx8MTY0NjkyNjI1Mw&amp;ixlib=rb-1.2.1&amp;h=400"
              project_title="Coca-Colla Next Door Campaign - conceptual"
              rootClassName="portofolio-card-root-class-name2"
            ></portofolio-card>
            <portofolio-card
              image_src="https://images.unsplash.com/photo-1545231027-637d2f6210f8?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDF8fHN0YXJidWNrc3xlbnwwfHx8fDE2NDY5MjYyMzc&amp;ixlib=rb-1.2.1&amp;h=400"
              project_title="Starbucks secret is a smile when you get your latte"
              rootClassName="portofolio-card-root-class-name1"
            ></portofolio-card>
          </div>
        </div>
      </div>
      <div class="home-about section-container">
        <div class="home-max-width3 max-content-container">
          <div class="home-text-container2">
            <span class="home-text25">about us</span>
            <h2 class="home-text26 heading2">
              <span>
                We build brands with
                <span v-html="rawcdry"></span>
              </span>
              <br />
              <span>purpose and impact</span>
            </h2>
            <span class="home-text30">
              We are a full-service digital creative agency with brick and mortar
              offices and plenty of in-house talent.
            </span>
            <div class="home-checklist">
              <div class="home-check-item">
                <svg viewBox="0 0 1024 1024" class="home-icon04">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="home-text31">
                  Quality services and support all time
                </span>
              </div>
              <div class="home-check-item1">
                <svg viewBox="0 0 1024 1024" class="home-icon06">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="home-text32">Long-term strategy development</span>
              </div>
              <div class="home-check-item2">
                <svg viewBox="0 0 1024 1024" class="home-icon08">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="home-text33">FREE Brand Audit for startups</span>
              </div>
              <div class="home-check-item3">
                <svg viewBox="0 0 1024 1024" class="home-icon10">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="home-text34">Over 10 years in the business</span>
              </div>
              <div class="home-check-item4">
                <svg viewBox="0 0 1024 1024" class="home-icon12">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="home-text35">Future-Proofing Projects</span>
              </div>
              <div class="home-check-item5">
                <svg viewBox="0 0 1024 1024" class="home-icon14">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="home-text36">Support in any implementation</span>
              </div>
            </div>
          </div>
          <div class="home-image-container">
            <img
              alt="image"
              src="/playground_assets/rectangle%20109-1000w.png"
              class="home-image6"
            />
          </div>
        </div>
      </div>
      <div class="home-process section-container">
        <div class="home-max-width4 max-content-container">
          <span class="home-text37">Our process</span>
          <h2 class="home-text38 heading2">
            <span>
              We use a simple three step process.
              <span v-html="rawwlhx"></span>
            </span>
            <br />
            <span>Take a look.</span>
          </h2>
          <div class="home-step">
            <span class="home-text42">01</span>
            <div class="home-container5">
              <span class="home-text43">Finding the best idea</span>
              <span class="home-text44">
                There are countless businesses already in existence, so it’s very
                likely that you won’t be the first person to think of an idea or
                product. There are countless businesses already in existence, so
                it’s very likely that you won’t be the first person to think of an
                idea or product.
                <span v-html="rawduey"></span>
              </span>
            </div>
          </div>
          <div class="home-step1">
            <span class="home-text45">02</span>
            <div class="home-container6">
              <span class="home-text46">
                Intense Brain storming
                <span v-html="raw5azc"></span>
              </span>
              <span class="home-text47">
                Brainstorming is a process of toiling and generating new ideas
                alone or by holding intensive group discussions between team
                members in a team.
              </span>
            </div>
          </div>
          <div class="home-step2">
            <span class="home-text48">03</span>
            <div class="home-container7">
              <span class="home-text49">Strong design execution</span>
              <span class="home-text50">
                As a creative, using your professional judgement, you should begin
                filtering your various ideas and designs, retaining the strongest
                relevant material.
              </span>
            </div>
          </div>
        </div>
      </div>
      <div class="section-container">
        <div class="home-max-width5 max-content-container">
          <span class="home-text51">from blog</span>
          <h2 class="home-text52 heading2">
            <span>Our latest articles and resources</span>
          </h2>
          <span class="home-text54">
            <span>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt
              <span v-html="raw7ka2"></span>
            </span>
            <br />
            <span>
              ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
              nostrud exercitation.
            </span>
          </span>
          <button class="home-primary2 button-secondary button-lg button">
            Explore the blog
          </button>
          <div class="home-blog-cards-container">
            <blog-card rootClassName="blog-card-root-class-name"></blog-card>
            <blog-card
              text1="Aug 14, 2022"
              button="advertising"
              image_src="/playground_assets/rectangle%2099%20%5B1%5D-1500w.png"
              rootClassName="blog-card-root-class-name1"
            ></blog-card>
            <blog-card
              text1="Jul 12, 2022"
              button="Branding"
              image_src="/playground_assets/unsplash_h7qmwoxf6z8-1500w.png"
            ></blog-card>
          </div>
        </div>
      </div>
      <div class="home-banner section-container">
        <div class="home-max-width6 max-content-container">
          <span class="home-text58">what are you waiting?</span>
          <h2 class="home-text59 heading2"><span>Let’s collaborate!</span></h2>
          <span class="home-text61">
            <span>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt
              <span v-html="rawr9nz"></span>
            </span>
            <br />
            <span>
              ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
              nostrud exercitation.
            </span>
          </span>
          <button class="home-primary3 button-lg button-secondary-white button">
            Contact us
          </button>
        </div>
      </div>
    </main>
    <div class="section-container">
      <div class="max-content-container">
        <div class="home-top-part">
          <div class="home-links-container">
            <div class="home-product-container">
              <span class="home-text65">Product</span>
              <span class="home-text66">About</span>
              <span class="home-text67">Portofolio</span>
              <span>Blog</span>
            </div>
            <div class="home-navigate-container">
              <span class="home-text69">Navigate</span>
              <span class="home-text70">Copyrights</span>
              <span class="home-text71">Sitemap</span>
              <span>Privacy Policy</span>
            </div>
            <div class="home-contact-container">
              <span class="home-text73">Contact Us</span>
              <span class="home-text74">
                <span>2157 Village View</span>
                <br />
                <span>
                  Drive, Old Fort
                  <span v-html="rawl4kn"></span>
                </span>
                <br />
                <span>
                  Myers Florida
                  <span v-html="rawft6l"></span>
                </span>
                <br />
                <span>33901</span>
              </span>
            </div>
          </div>
          <div class="home-subscribe-container">
            <span class="home-text82">Subscribe to our newsletter</span>
            <input
              type="text"
              placeholder="Enter your e-mail address"
              class="home-textinput input"
            />
            <button class="button-primary button">Subscribe</button>
          </div>
        </div>
      </div>
      <div class="home-separator"></div>
      <footer class="home-max-width8 max-content-container">
        <img
          alt="image"
          src="/playground_assets/logo1-200h.png"
          class="home-image7"
        />
        <span class="home-text83">
          <span>
            All rights recived @
            <span v-html="raw47qc"></span>
          </span>
          <span class="home-text85">
            aesthetics
            <span v-html="raw8mwd"></span>
          </span>
          <span>
            | Designed by
            <span v-html="rawejxy"></span>
          </span>
          <span class="home-text87">Bhargav</span>
          <span><span v-html="rawwluu"></span></span>
        </span>
      </footer>
    </div>
  </div>
</template>

<script>
import AppNavigation from '../components/navigation'
import ServicesCard from '../components/services-card'
import PortofolioCard from '../components/portofolio-card'
import BlogCard from '../components/blog-card'

export default {
  name: 'Home',
  components: {
    AppNavigation,
    ServicesCard,
    PortofolioCard,
    BlogCard,
  },

  data() {
    return {
      raw1qvr: ' ',
      rawxyn1: ' ',
      rawcdry: ' ',
      rawwlhx: ' ',
      rawduey: ' ',
      raw5azc: ' ',
      raw7ka2: ' ',
      rawr9nz: ' ',
      rawl4kn: ' ',
      rawft6l: ' ',
      raw47qc: ' ',
      raw8mwd: ' ',
      rawejxy: ' ',
      rawwluu: ' ',
    }
  },

  head: {
    title: 'Creative Agency Page',
    meta: [
      {
        property: 'og:title',
        content: 'Creative Agency Page',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  position: relative;
  min-height: 100vh;
  overflow-x: hidden;
  align-items: center;
  flex-direction: column;
}
.home-main {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-hero {
  position: relative;
  padding-top: 128px;
}
.home-max-width {
  margin-top: var(--dl-space-space-threeunits);
}
.home-heading-container {
  flex: 1;
  display: flex;
  max-width: 100%;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text {
  text-align: center;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text03 {
  color: var(--dl-color-scheme-black);
  font-size: 18px;
  text-align: center;
  line-height: 1.44;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-primary {
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-gallery {
  width: 100%;
  display: flex;
  grid-gap: 20px;
  align-items: stretch;
}
.home-container1 {
  width: 25%;
  align-self: stretch;
}
.home-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-container2 {
  width: 25%;
  display: flex;
  grid-gap: 20px;
  align-items: stretch;
  flex-direction: column;
}
.home-image1 {
  width: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-image2 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-container3 {
  width: 50%;
  display: flex;
  grid-gap: 20px;
  flex-direction: column;
}
.home-image3 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-container4 {
  width: 100%;
  display: flex;
  grid-gap: 20px;
}
.home-image4 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-image5 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-services {
  display: flex;
  padding-top: var(--dl-space-space-fiveunits);
  flex-direction: column;
  background-color: var(--dl-color-scheme-lightbrown);
}
.home-max-width1 {
  flex-direction: column;
}
.home-heading-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-end;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: row;
  justify-content: space-between;
}
.home-text-container {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text07 {
  color: var(--dl-color-scheme-brown);
  font-style: normal;
  text-align: center;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.home-controls {
  display: grid;
  grid-gap: 12px;
  grid-template-columns: 1fr 1fr;
}
.home-icon {
  width: 16px;
  height: 16px;
}
.home-icon02 {
  width: 16px;
  height: 16px;
}
.home-cards-container {
  width: 100%;
  display: flex;
  grid-gap: 20px;
}
.home-max-width2 {
  flex-direction: column;
}
.home-text-container1 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text12 {
  color: var(--dl-color-scheme-brown);
  font-style: normal;
  text-align: center;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.home-text13 {
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text15 {
  color: var(--dl-color-scheme-black80);
  text-align: center;
  line-height: 26px;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-tab-selector-header {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-threeunits);
  flex-direction: row;
  justify-content: center;
}
.home-text19 {
  margin-right: 30px;
}
.home-text20 {
  margin-right: 30px;
}
.home-text21 {
  margin-right: 30px;
}
.home-text22 {
  margin-right: 30px;
}
.home-text23 {
  margin-right: 30px;
}
.home-tab-selector-cards-container {
  width: 100%;
  display: grid;
  grid-row-gap: 40px;
  grid-column-gap: 20px;
  grid-template-rows: repeat(2, 1fr);
  grid-template-columns: repeat(3, 1fr);
}
.home-about {
  background-color: var(--dl-color-scheme-lightbrown);
}
.home-max-width3 {
  flex-direction: row;
  justify-content: space-between;
}
.home-text-container2 {
  flex: 1;
  width: 40%;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-unit);
  flex-direction: column;
}
.home-text25 {
  color: var(--dl-color-scheme-brown);
  font-style: normal;
  text-align: center;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.home-text26 {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text30 {
  color: var(--dl-color-scheme-black80);
  line-height: 26px;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-checklist {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-check-item {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-icon04 {
  fill: var(--dl-color-scheme-brown);
  width: 18px;
  height: 18px;
  margin-right: var(--dl-space-space-unit);
}
.home-text31 {
  font-style: normal;
  font-weight: 500;
}
.home-check-item1 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-icon06 {
  fill: var(--dl-color-scheme-brown);
  width: 18px;
  height: 18px;
  margin-right: var(--dl-space-space-unit);
}
.home-text32 {
  font-style: normal;
  font-weight: 500;
}
.home-check-item2 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-icon08 {
  fill: var(--dl-color-scheme-brown);
  width: 18px;
  height: 18px;
  margin-right: var(--dl-space-space-unit);
}
.home-text33 {
  font-style: normal;
  font-weight: 500;
}
.home-check-item3 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-icon10 {
  fill: var(--dl-color-scheme-brown);
  width: 18px;
  height: 18px;
  margin-right: var(--dl-space-space-unit);
}
.home-text34 {
  font-style: normal;
  font-weight: 500;
}
.home-check-item4 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-icon12 {
  fill: var(--dl-color-scheme-brown);
  width: 18px;
  height: 18px;
  margin-right: var(--dl-space-space-unit);
}
.home-text35 {
  font-style: normal;
  font-weight: 500;
}
.home-check-item5 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-icon14 {
  fill: var(--dl-color-scheme-brown);
  width: 18px;
  height: 18px;
  margin-right: var(--dl-space-space-unit);
}
.home-text36 {
  font-style: normal;
  font-weight: 500;
}
.home-image6 {
  flex: 1;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-process {
  background-color: var(--dl-color-scheme-lightblue);
}
.home-max-width4 {
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-between;
}
.home-text37 {
  color: var(--dl-color-scheme-white);
  font-style: normal;
  text-align: center;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.home-text38 {
  color: var(--dl-color-scheme-white);
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-step {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  border-color: rgba(255, 255, 255, 0.2);
  border-width: 1px;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: row;
  padding-bottom: 53px;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 1px;
}
.home-text42 {
  color: var(--dl-color-scheme-white);
  font-size: 64px;
  font-style: normal;
  font-weight: 500;
  line-height: 61px;
  margin-right: 180px;
}
.home-container5 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text43 {
  color: var(--dl-color-scheme-white);
  font-size: 24px;
  line-height: 31px;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text44 {
  color: var(--dl-color-scheme-white80);
}
.home-step1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  border-color: rgba(255, 255, 255, 0.2);
  border-width: 1px;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: row;
  padding-bottom: 53px;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 1px;
}
.home-text45 {
  color: var(--dl-color-scheme-white);
  font-size: 64px;
  font-style: normal;
  font-weight: 500;
  line-height: 61px;
  margin-right: 180px;
}
.home-container6 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text46 {
  color: var(--dl-color-scheme-white);
  font-size: 24px;
  line-height: 31px;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text47 {
  color: var(--dl-color-scheme-white80);
}
.home-step2 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  border-color: rgba(255, 255, 255, 0.2);
  border-width: 1px;
  flex-direction: row;
  padding-bottom: 53px;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 1px;
}
.home-text48 {
  color: var(--dl-color-scheme-white);
  font-size: 64px;
  font-style: normal;
  font-weight: 500;
  line-height: 61px;
  margin-right: 180px;
}
.home-container7 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text49 {
  color: var(--dl-color-scheme-white);
  font-size: 24px;
  line-height: 31px;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text50 {
  color: var(--dl-color-scheme-white80);
}
.home-max-width5 {
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.home-text51 {
  color: var(--dl-color-scheme-brown);
  font-style: normal;
  text-align: center;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.home-text52 {
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text54 {
  color: var(--dl-color-scheme-black80);
  text-align: center;
  line-height: 26px;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-primary2 {
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-blog-cards-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-banner {
  background-color: var(--dl-color-scheme-brown);
}
.home-max-width6 {
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.home-text58 {
  color: var(--dl-color-scheme-white);
  font-style: normal;
  text-align: center;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.home-text59 {
  color: var(--dl-color-scheme-white);
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text61 {
  color: var(--dl-color-scheme-white);
  text-align: center;
  line-height: 26px;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-primary3 {
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-top-part {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: row;
  justify-content: space-between;
}
.home-links-container {
  width: 50%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-product-container {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text65 {
  color: var(--dl-color-scheme-brown);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text66 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text67 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-navigate-container {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text69 {
  color: var(--dl-color-scheme-brown);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text70 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text71 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-contact-container {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text73 {
  color: var(--dl-color-scheme-brown);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text74 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-subscribe-container {
  flex: 0 0 auto;
  width: 35%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text82 {
  color: var(--dl-color-scheme-brown);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-textinput {
  outline: none;
  align-self: stretch;
  padding-top: 4px;
  border-color: rgba(0, 0, 0, 0.1);
  padding-left: 0px;
  border-radius: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  padding-bottom: 4px;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 1px;
}
.home-separator {
  width: 100%;
  height: 1px;
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
  background-color: #D9D9D9;
}
.home-max-width8 {
  flex-direction: row;
  justify-content: space-between;
}
.home-image7 {
  width: 100px;
  object-fit: cover;
}
.home-text83 {
  align-self: center;
}
.home-text85 {
  font-weight: 700;
}
.home-text87 {
  font-weight: 700;
}
@media(max-width: 991px) {
  .home-heading-container {
    max-width: 100%;
    margin-bottom: 42px;
  }
  .home-gallery {
    flex-direction: column;
  }
  .home-container1 {
    width: 100%;
  }
  .home-container2 {
    width: 100%;
    flex-direction: row;
  }
  .home-container3 {
    width: 100%;
    align-items: stretch;
  }
  .home-tab-selector-cards-container {
    grid-template-columns: repeat(2, 1fr);
  }
  .home-max-width3 {
    flex-direction: column;
  }
  .home-text-container2 {
    width: 100%;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-image-container {
    width: 100%;
  }
  .home-image6 {
    width: 100%;
  }
  .home-blog-cards-container {
    align-items: center;
    flex-direction: column;
  }
}
@media(max-width: 767px) {
  .home-text {
    font-size: 48px;
  }
  .home-container2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .home-image1 {
    height: 100%;
  }
  .home-tab-selector-cards-container {
    grid-template-columns: 1fr;
  }
  .home-text42 {
    margin-right: var(--dl-space-space-fourunits);
  }
  .home-text45 {
    margin-right: var(--dl-space-space-fourunits);
  }
  .home-text48 {
    margin-right: var(--dl-space-space-fourunits);
  }
  .home-top-part {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-links-container {
    width: 100%;
    align-items: flex-start;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
    flex-direction: row;
  }
  .home-subscribe-container {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .home-text42 {
    margin-right: var(--dl-space-space-twounits);
  }
  .home-text45 {
    margin-right: var(--dl-space-space-twounits);
  }
  .home-text48 {
    margin-right: var(--dl-space-space-twounits);
  }
  .home-top-part {
    align-items: center;
    flex-direction: column;
  }
  .home-contact-container {
    align-items: flex-start;
    margin-bottom: 0px;
  }
  .home-max-width8 {
    flex-direction: column;
  }
  .home-image7 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text83 {
    text-align: center;
  }
}
</style>
