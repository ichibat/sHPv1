<template>
  <div>
    <header class="l-header">
      <ul class="c-header">
        <li class="c-header__item--left">
          <nuxt-link to="/">
            <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" class="c-header__logo" />
            <span class="c-header__name">すみれホームケアクリニック</span>
          </nuxt-link>
        </li>
        <li class="c-header__item--right">
          <nuxt-link to="/" class="c-header__navName button">トップページ</nuxt-link>
        </li>
        <li class="c-header__item--right c-header__navName">
          <nuxt-link to="/about" class="c-header__navName button">クリニックのご紹介</nuxt-link>
        </li>
        <li class="c-header__item--right c-header__navName">
          <nuxt-link to="/contacts" class="c-header__navName button">お問い合わせ</nuxt-link>
        </li>
        <li class="c-header__item--right c-header__navName">
          <nuxt-link to="/blog" class="c-header__navName button">ブログ</nuxt-link>
        </li>
      </ul>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
