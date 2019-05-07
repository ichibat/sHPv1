<template>
  <nav class="navbar is-white">
    <div class="container">
      <div class="navbar-brand">
        <nuxt-link to="/" class="navbar-item" >
          <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" width="28" height="28">

          <span>すみれホームケアクリニック</span>
        </nuxt-link>

        <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-start">
          <nuxt-link to="/" class="navbar-item">トップページ</nuxt-link>
          <nuxt-link to="/about" class="navbar-item">クリニックのご紹介</nuxt-link>
          <nuxt-link to="/contacts" class="navbar-item">お問い合わせ</nuxt-link>
          <nuxt-link to="/blog" class="navbar-item">ブログ</nuxt-link>
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link" href="/documentation/overview/start/">More</a>
            <div class="navbar-dropdown is-boxed">
              <a class="navbar-item" href="/documentation/overview/start/">Mechandise</a>
              <a class="navbar-item" href="https://bulma.io/documentation/modifiers/syntax/">Extras</a>
              <a class="navbar-item" href="https://bulma.io/documentation/columns/basics/">Media</a>
            </div>
          </div>
        </div>

        <div class="navbar-end">
          <div class="navbar-item">
            <div class="field">
              <div class="control">
                <input class="input" type="text" placeholder="search . . .">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
</style>
