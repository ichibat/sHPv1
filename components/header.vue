<template>
  <div>
    <!-- <h1 class="title">練馬およびその周辺地域の在宅医療 すみれホームケアクリニック－患者様の「おうちで過ごしたい」を医師が24時間サポートします－</h1> -->
    <nav>
      <div class="b2-1pad">
        <nuxt-link to="/">
          <img src="~/assets/sumire_rogo.png" alt="すみれホームケアクリニックロゴ" width="70" height="auto">
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
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
