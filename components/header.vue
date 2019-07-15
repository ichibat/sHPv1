<template>
  <div>
    <header class="navbar">
      <div class="navbar-brand">
        <nuxt-link to="/" class="navbar-item">
          <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" class="c-header__logo" />
          <span class="c-header__name">すみれホームケアクリニック</span>
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
      <div class="navbar-menu">
        <li class="c-header__item--right">
          <nuxt-link to="/" class="c-header__navName button is-rounded">トップページ</nuxt-link>
        </li>
        <li class="c-header__item--right c-header__navName">
          <nuxt-link to="/about" class="c-header__navName button is-rounded">クリニックのご紹介</nuxt-link>
        </li>
        <li class="c-header__item--right c-header__navName">
          <nuxt-link to="/contacts" class="c-header__navName button is-rounded">お問い合わせ</nuxt-link>
        </li>
        <li class="c-header__item--right c-header__navName">
          <nuxt-link to="/blog" class="c-header__navName button is-rounded">ブログ</nuxt-link>
        </li>
      </div>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
