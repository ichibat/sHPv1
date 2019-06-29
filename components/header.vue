<template>
  <div class="header">
    <header>
      <div class>
        <nuxt-link to="/">
          <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" class="c-header__logo">
          <span>すみれホームケアクリニック</span>
        </nuxt-link>
      </div>

      <ul class="c-header__list">
        <li class="c-header__item">
          <nuxt-link to="/">トップページ</nuxt-link>
        </li>
        <li class="c-header__item">
          <nuxt-link to="/about">クリニックのご紹介</nuxt-link>
        </li>
        <li class="c-header__item">
          <nuxt-link to="/contacts">お問い合わせ</nuxt-link>
        </li>
        <li class="c-header__item">
          <nuxt-link to="/blog">ブログ</nuxt-link>
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
