<template>
  <div>
    <header class="navbar">
      <div class="navbar-brand">
        <nuxt-link to="/" class="navbar-item">
          <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" width="102" height="100" />
          <div class="navbar-item c-header__name">すみれホームケアクリニック</div>
        </nuxt-link>

        <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div class="navbar-menu is-size-3">
        <div class="navbar-start">
          <div class="navbar-itme">
            <nuxt-link to="/">トップページ</nuxt-link>
          </div>
        </div>
        <div class="navbar-itmem">
          <nuxt-link to="/about">クリニックのご紹介</nuxt-link>
        </div>
        <div class="navbar-itmem">
          <nuxt-link to="/contacts">お問い合わせ</nuxt-link>
        </div>
        <div class="navbar-itmem">
          <nuxt-link to="/blog">ブログ</nuxt-link>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
