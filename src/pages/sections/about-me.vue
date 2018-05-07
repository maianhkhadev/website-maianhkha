<template>
  <div class="section">
    <div class="container">
      <div class="section-header row">
        <div class="col-xl-4 mx-auto">
          <div class="title-container">
            <div class="title">About Me</div>
          </div>
        </div>
      </div>
      <div class="section-content row">
        <div class="col-xl-6">
          <img class="w-100" src="~@/assets/images/page-home/section-02/im-01.jpg" alt=""/>
        </div>
        <div class="col-xl-6">
          <div class="content">
            I'm a <b>Front-end and UI Developer</b> from Ho Chi Minh City, Vietnam. I Have more than 4 year of working experience as a web developer. This is some information about me:
          </div>
          <ul>
            <li><span class="">Name:</span> Mai Anh Kha</li>
            <li><span class="">Email:</span> maianhkha.dev@gmail.com</li>
            <li><span class="">Phone:</span> <a href="tel:01218455821">01218455821</a></li>
            <li><span class="">Date of birth:</span> 18 November 1992</li>
            <li><span class="">Nationality:</span> Vietnam</li>
          </ul>
          <a class="btn btn-amber button" href="/static/Mai-Anh-Kha-CV.pdf" download>DOWNLOAD RESUME</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .section {

    .section-content {

      img {
        @media screen and (max-width: 600px) {
          margin-bottom: 1.25rem;
        }
      }
      ul {
        list-style-position: outside;
        list-style: none outside none;
        padding-left: 0;
        margin-left: 0;
        margin-right: 0;
        margin-top: 8%;
        margin-bottom: 8%;

        li {
          border-bottom: 0.0625rem solid rgba(#000000, 0.1);
          padding-top: 0.5rem;
          padding-bottom: 0.5rem;

          span {
            display: inline-block;
            min-width: 8rem;
            font-weight: 600;
          }
          a {
            color: #000000;
            text-decoration: underline;
          }
        }
      }
      .button {
        font-size: 0.875rem;
        border-radius: unset;
        padding: 0.625rem 1.375rem;
      }
    }
  }
</style>
