<template>
  <div>
    <div class="section-01 verticle-middle">
      <div class="container">
        <div class="row">
          <div class="col-xl-6">
            <div class="title">
              <span class="color-amber">Hello</span> I'm
              <mai-anh-kha></mai-anh-kha>
            </div>
            <div class="subtitle"></div>
          </div>
        </div>
      </div>
    </div>

    <section-about-me></section-about-me>

    <div class="section section-skills">
      <div class="container">
        <div class="section-header row">
          <div class="col-xl-4 mx-auto">
            <div class="title-container">
              <div class="title">What I can do</div>
            </div>
          </div>
        </div>
        <div class="section-content row">
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">PHP Framework</div>
              <div class="content">Can use popular frameworks like Laravel</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">API</div>
              <div class="content">Knowledge of API and OAuth 2.0</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">HTML - CSS - JS</div>
              <div class="content">Proficient in Javascript, HTML5 and CSS3</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">JS Framework</div>
              <div class="content">Knowledge of Javascript framework (Vue, React)</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">SASS</div>
              <div class="content">Experience with CSS Preprocessors (SASS, LESS)</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">Responsive</div>
              <div class="content">Comfortable with responsive design and cross browser</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">Version control system</div>
              <div class="content">Knowledge of SVN / GIT for source versioning</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">SEO</div>
              <div class="content">Understanding of SEO principles</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">PSD to HTML</div>
              <div class="content">Convert PSD - Figma to HTML</div>
            </div>
          </div>
          <div class="col-xl-3">
            <div class="skill">
              <div class="title">UX - UI</div>
              <div class="content">Strong sense of web design and user experience</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <div class="container">
        <div class="section-header row">
          <div class="col-xl-4 mx-auto">
            <div class="title-container">
              <div class="title">My responsibility</div>
            </div>
          </div>
        </div>
        <div class="section-content row">
          <div class="col-xl-6">
            <div class="work">
              <b>1.</b> Keep myself updated with technology
            </div>
          </div>
          <div class="col-xl-6">
            <div class="work">
              <b>2.</b> Improving performance of front-end work on projects
            </div>
          </div>
          <div class="col-xl-6">
            <div class="work">
              <b>3.</b> Communicate challenges to other colleagues
            </div>
          </div>
          <div class="col-xl-6">
            <div class="work">
              <b>4.</b> Choosing framework and technology for projects
            </div>
          </div>
          <div class="col-xl-6">
            <div class="work">
              <b>5.</b> Technical support for other teams
            </div>
          </div>
          <div class="col-xl-6">
            <div class="work">
              <b>6.</b> Write clean and well organized code
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="parallax"></div>

    <section-demos></section-demos>

    <section-contact-me></section-contact-me>
  </div>
</template>

<style lang="scss">
  .section {
    padding-top: 6rem;
    padding-bottom: 6rem;

    .section-header {
      text-align: center;
      margin-bottom: 4rem;

      .title-container {
        position: relative;

        &::before {
          content: '';
          position: absolute;
          top: 50%;
          left: auto;
          right: 0;
          height: 0;
          width: 100%;
          border-top: 0.25rem double rgba(#000000, .15);
          z-index: -2;
        }
      }
      .title {
        display: inline-block;
        background-color: #ffffff;
        font-size: 1.5rem;
        font-weight: 700;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 0.125rem;
        padding-left: 1.25rem;
        padding-right: 1.25rem;
      }
      .content {
        color: #7f7f7f;
        font-size: 1rem;
        margin-top: 2rem;
      }
    }
  }
</style>

<style lang="scss" scoped>
  .verticle-middle {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .section-01 {
    position: relative;
    background-image: url('~@/assets/images/page-home/cover.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    padding-top: 6rem;
    padding-bottom: 6rem;

    @media screen and (max-width: 600px) {
      align-items: flex-start;
    }

    .title {
      color: #ffffff;
      font-size: 4.25rem;
      font-weight: 700;
      line-height: 1.1;
      margin-bottom: 1.25rem;

      @media screen and (max-width: 600px) {
        font-size: 3.75rem;
      }
    }
    .subtitle {
      color: #ffffff;
      font-size: 1.25rem;
      text-transform: uppercase;
      height: 2rem;
    }
  }

  .section-skills {
    padding-bottom: 4.75rem;
  }

  .parallax {
    background-image: url('~@/assets/images/page-home/im-01.jpg');
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    filter: grayscale(100%);
    padding-top: 15rem;
    padding-bottom: 15rem;
  }

  .skill {
    padding: 1.25rem;

    .title {
      color: #000000;
      font-size: 0.875rem;
      font-weight: 600;
      text-transform: uppercase;
      margin-bottom: 0.5rem;
    }
    .content {
      color: #626262;
      font-size: 0.875rem;
    }
  }
  .work {
    padding-top: 1.5rem;
    padding-bottom: 1.5rem;
  }
</style>

<script>
  import MaiAnhKha from '@/components/mai-anh-kha/index'
  import Typed from 'typed.js'

  import SectionAboutMe from './sections/about-me'
  import SectionContactMe from './sections/contact-me'
  import SectionDemos from './sections/demos'

  export default {
    components: {
      'mai-anh-kha': MaiAnhKha,
      'section-about-me': SectionAboutMe,
      'section-contact-me': SectionContactMe,
      'section-demos': SectionDemos
    },
    mounted () {
      let typed = new Typed('.section-01 .subtitle', {
        strings: ['A Front-end and UI Developer'],
        typeSpeed: 40
      })
    }
  }
</script>
