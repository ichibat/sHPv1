<template>
  <div class="header">
    <header>
      <div class>
        <nuxt-link to="/">
          <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" class="c-header__logo">
          <span>すみれホームケアクリニック</span>
        </nuxt-link>
      </div>

      <ul>
        <li class="current">
          <nuxt-link to="/" class="navbar-item">トップページ</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about" class="navbar-item">クリニックのご紹介</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/contacts" class="navbar-item">お問い合わせ</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/blog" class="navbar-item">ブログ</nuxt-link>
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
