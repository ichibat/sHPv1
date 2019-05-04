<template>
  <div>
    <nav class="navbar is-white">
      <div class="navbar-brand">
        <a class="navbar-item" href="https://bulma.io">
          <img
            src="~/assets/sumire_rogo.png"
            alt="Bulma: a modern CSS framework based on Flexbox"
            width="28"
            height="28"
          >
          <span>
            <strong>すみれホームケアクリニック</strong>
          </span>
        </a>

        <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item" href="/band">トップページ</a>
          <a class="navbar-item" href="/about">クリニックのご紹介</a>
          <a class="navbar-item" href="https://bulma.io/">お問い合わせ</a>
          <a class="navbar-item" href="https://bulma.io/">ブログ</a>
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
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
