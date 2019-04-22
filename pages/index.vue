<template>
  <!-- <section class="container"> -->
  <section>
    <div class="container">
      <!-- <logo/> -->
      <div class="inner">
        <p
          class="text-white bg-purple"
        >練馬およびその周辺地域の在宅医療 すみれホームケアクリニック‐患者様の「おうちで過ごしたい」を医師が24時間サポートします．‐</p>
        <div class="bg-light">
          <img src="~/assets/sumire_2_2.png" class="w-25">
          <span class="float-right">
            電話での相談は随時受け付けております.
            <br>
          </span>
          <span class="text-purple float-right">TEL03-6904-5828．</span>
        </div>
        <div>
          <img src="~/assets/mainImage.jpg">
        </div>
        <div class="bg-success d-flex flex-row">
          <img src="~/assets/top_copy.gif" class="bg-info">
          <span class="bg-danger">
            近年様々な病気が医学の進歩で克服されましたが、その結果継続的に治療を受け人生を過ごす方が少なくありません。
            認知症、脳卒中などの神経疾患や、がんが代表的ですが、患者さんにとっては治療が生活や人生の全てではなく、できれば住み慣れた家で生活したいいと考える方も増えています。こうした変化の背景として、従来入院でしかできなかった治療が在宅でもできるようになったことが挙げられます。更に自分の生活のペースを変えずに家族に囲まれた環境で療養することで、生活の質の向上も期待できます。
            当院では、通院が困難な方や在宅での療養を希望される方に定期的な訪問診療をすることにより、最適な医療を提供したいと考えています。
          </span>
        </div>

        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
          <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a>
        </div>
        <link
          rel="stylesheet"
          href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
          integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
          crossorigin="anonymous"
        >
      </div>
    </div>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style>
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: left;
} */

.inner {
  width: 980px;
}
.bg-purple {
  background-color: rgb(143, 125, 184);
}

.text-purple {
  color: rgb(143, 125, 184);
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
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

.example {
  float: left;
}
</style>
