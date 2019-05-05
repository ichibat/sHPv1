<template>
  <!-- <section class="container"> -->
  <section>
    <Header/>
    <!-- <logo/> -->
    <div class="jumbotron-extend1 jumbotron">
      <div class="container">
        <h1 class="lead">練馬およびその周辺地域の在宅医療---すみれホームケアクリニック</h1>
        <div>
          <img src="~/assets/sumire_2_2.png" class="w-25">
          <p class="float-right">電話での相談は随時受け付けております.</p>
          <br>
          <p class="float-right lead">電話：03-6904-5828</p>
        </div>

        <nav class="navbar navbar-expand-lg navbar-light bg-light">
          <a class="navbar-brand" href="#">トップページ</a>
          <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
              <li class="nav-item active">
                <a class="nav-link" href="#">
                  クリニックのご紹介
                  <span class="sr-only">(current)</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">診療のご紹介</a>
              </li>

              <li class="nav-item active">
                <a class="nav-link" href="#">
                  お問い合わせ
                  <span class="sr-only">(current)</span>
                </a>
              </li>

              <li class="nav-item active">
                <a class="nav-link" href="#">
                  ブログ
                  <span class="sr-only">(current)</span>
                </a>
              </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
              <input
                class="form-control mr-sm-2"
                type="search"
                placeholder="Search"
                aria-label="Search"
              >
              <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
            </form>
          </div>
        </nav>
      </div>
    </div>
    <img src="~/assets/mainImage.jpg">
    <div class="mt-3">
      <div class="row inner">
        <img src="~/assets/top_copy.gif" class="bg-pink col-md-6">
        <span class="bg-danger col-md-6">
          近年様々な病気が医学の進歩で克服されましたが、その結果継続的に治療を受け人生を過ごす方が少なくありません。
          認知症、脳卒中などの神経疾患や、がんが代表的ですが、患者さんにとっては治療が生活や人生の全てではなく、できれば住み慣れた家で生活したいいと考える方も増えています。こうした変化の背景として、従来入院でしかできなかった治療が在宅でもできるようになったことが挙げられます。更に自分の生活のペースを変えずに家族に囲まれた環境で療養することで、生活の質の向上も期待できます。
          当院では、通院が困難な方や在宅での療養を希望される方に定期的な訪問診療をすることにより、最適な医療を提供したいと考えています。
        </span>
      </div>
    </div>

    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    >
  </section>
</template>

<script>
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

/* .jumbotron-extend1 {
  padding-top: 12px !important;
  padding-bottom: 120px !important;
  background-color: white important;
}

.bg-purple {
  background-color: rgb(143, 125, 184);
}

.bg-pink {
  background-color: pink;
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
} */
</style>
