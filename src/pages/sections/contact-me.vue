<template>
  <div class="section">
    <div class="container">
      <div class="section-header row">
        <div class="col-xl-4 mx-auto">
          <div class="title-container">
            <div class="title">Contact me</div>
          </div>
        </div>
      </div>
      <div class="section-content row">
        <div class="col-xl-6">
          <div class="form-group">
            <input type="email" class="form-control" placeholder="YOUR NAME">
          </div>
          <div class="form-group">
            <input type="email" class="form-control" placeholder="YOUR EMAIL">
          </div>
        </div>
        <div class="col-xl-6">
          <div class="form-group">
            <textarea class="form-control" rows="4" placeholder="YOUR MESSAGE"></textarea>
          </div>
        </div>
        <div class="col-xl-6">
          <span class="required">*Please complete all fields correctly</span>
        </div>
        <div class="col-xl-6 text-xl-right mt-2 mt-xl-0">
          <button class="btn btn-amber" v-on:click="send">Send Message</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .section {

    .section-content{

      .form-group {
        margin-bottom: 1.25rem;

        .form-control {
          padding: 0.75rem 1rem;
        }
      }
      button {
        font-size: 0.875rem;
        border-radius: unset;
        padding: 0.625rem 1.375rem;
      }
    }
  }
</style>

<script>
  export default {
    methods: {
      send: function () {
        alert('Comming Soon')
      }
    }
  }
</script>
