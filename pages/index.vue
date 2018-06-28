<template>
  <section class="container">
    <div>
      <h1 class="title">
        THRIZINO
      </h1>
      <div class="image_wrapper">
        <img :src="thrizinoImage" class="thrizino_img"/>
      </div>
      <h3 class="subtitle">
        Coming soon!
      </h3>
      <div class="links">
        <a
          href="mailto:nyorikakar@gmail.com?Subject=Thrizino%20contact" target="_top"
          class="button--green">Contact</a>
      </div>
    </div>
  </section>
</template>

<script>
  import thrizinoImage from '~/assets/images/thrizino-brush-1.jpg'

  export default {

    data() {
      return {
        thrizinoImage
      }
    }

  }
</script>

<style>
  .container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    display: block;
    font-weight: 300;
    font-size: 50px;
    color: #35495e;
    letter-spacing: 10px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }

  .image_wrapper {
    max-width: 700px;
    padding: 16px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    /*border: 1px solid blue;*/
  }

  .thrizino_img {
    /*border: 1px solid red;*/
    max-width: 100%;
    max-height: 100%;
  }
</style>
