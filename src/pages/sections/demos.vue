<template>
  <div class="section">
    <div class="container">
      <div class="section-header row">
        <div class="col-xl-4 mx-auto">
          <div class="title-container">
            <div class="title">Playground</div>
          </div>
          <div class="content">
            This place where I put my demos. Something I do for client or my interest things.
          </div>
        </div>
      </div>
      <div class="section-content row">
        <div class="col-xl-3">
          <div class="project">
            <a href="https://panzani.vn/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-01.jpg" alt=""/>
            </a>
            <a class="name" href="https://panzani.vn/" target="_blank">Panzani</a>
            <div class="date">SEPTEMBER 2017</div>
            <span>Nuxt</span><span>Zend</span>
          </div>
        </div>
        <div class="col-xl-3">
          <div class="project">
            <a href="https://wallstreetenglish.edu.vn/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-02.jpg" alt=""/>
            </a>
            <a class="name" href="https://wallstreetenglish.edu.vn/" target="_blank">Wall Street English</a>
            <div class="date">AUGUST 2017</div>
            <span>Zend</span>
          </div>
        </div>
        <div class="col-xl-3">
          <div class="project">
            <a href="http://www.andros-asia.com/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-03.jpg" alt=""/>
            </a>
            <a class="name" href="http://www.andros-asia.com/" target="_blank">Andros</a>
            <div class="date">JANUARY 2018</div>
            <span>Nuxt</span><span>Laravel</span>
          </div>
        </div>
        <div class="col-xl-3">
          <div class="project">
            <a href="https://www.laresidenciahotel.com/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-04.jpg" alt=""/>
            </a>
            <a class="name" href="https://www.laresidenciahotel.com/" target="_blank">La Residencia Hotel</a>
            <div class="date">DECEMBER 2017</div>
            <span>Vanilla</span><span>Zend</span>
          </div>
        </div>
        <div class="col-xl-3">
          <div class="project">
            <a href="http://foodnhotelhanoi.com/en-us/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-05.jpg" alt=""/>
            </a>
            <a class="name" href="http://foodnhotelhanoi.com/en-us/" target="_blank">FHH FOOD & HOTEL</a>
            <div class="date">05 SEPTEMBER 2017</div>
            <span>Vanilla</span>
          </div>
        </div>
        <div class="col-xl-3">
          <div class="project">
            <a href="http://the-bloom.maianhkha.com/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-06.jpg" alt=""/>
            </a>
            <a class="name" href="http://the-bloom.maianhkha.com/" target="_blank">The Bloom (BACKUP)</a>
            <div class="date">02 JANUARY 2018</div>
            <span>Vue</span>
          </div>
        </div>
        <div class="col-xl-3">
          <div class="project">
            <a href="http://bakery.maianhkha.com/" target="_blank">
              <img class="w-100" src="~@/assets/images/projects/im-07.jpg" alt=""/>
            </a>
            <a class="name" href="http://bakery.maianhkha.com/" target="_blank">Bakery (Demo)</a>
            <div class="date">12 MAY 2018</div>
            <span>React</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .section {
    padding-bottom: 3rem;
  }
  .project {
    margin-bottom: 3rem;

    img {
      margin-bottom: 0.75rem;
    }
    .name {
      color: #000000;
      font-size: 1rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.125rem;
    }
    .date {
      color: #797979;
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.125rem;
      margin-bottom: 0.5rem;
    }
    span {
      color: #797979;
      font-size: 0.75rem;
      border: 0.0625rem solid #e5e5e5;
      border-radius: 0.25rem;
      padding: 0.125rem 0.5rem;
      margin-right: 0.25rem;
    }
  }
</style>
