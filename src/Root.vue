<template>
  <div id="root">
    <router-view/>

    <footer>
      <div class="section-01">
        <div class="container">
          <div class="row">
            <div class="col-xl-12 text-center">
              <a class="mx-3" href="https://www.facebook.com/kha.mai.3">
                <img width="20" src="~@/assets/images/facebook.png" alt=""/>
              </a>
              <a class="mx-3" href="https://github.com/maianhkhadev">
                <img width="20" src="~@/assets/images/github.png" alt=""/>
              </a>
              <a class="mx-3" href="https://www.linkedin.com/in/anh-kha-mai-826104142/">
                <img width="20" src="~@/assets/images/linkedin.png" alt=""/>
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="section-02">
        <div class="container">
          <div class="row">
            <div class="col-6">
              © 2018 WEBSITE IS PROUDLY POWERED BY KHA MAI.
            </div>
            <div class="col-6 text-right">
              <b>KHA MAI</b>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Root'
}
</script>

<style lang="scss" src="@/assets/scss/root.scss"></style>

<style lang="scss" scoped>
  footer {

    .section-01 {
      background-color: #f4f4f4;
      padding-top: 1.75rem;
      padding-bottom: 1.75rem;
    }
    .section-02 {
      color: #7f7f7f;
      background-color: #252525;
      padding-top: 1.75rem;
      padding-bottom: 1.75rem;
    }
  }
</style>
