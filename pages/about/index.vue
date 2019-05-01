<template>
  <div>
    <header class="nav">
      <div class="nav-left">
        <span class="nav-item">
          <span class="fa fa-language"></span>一言SNS
        </span>
      </div>
      <div class="nav-right">
        <span class="nav-item">
          <div class="control has-addons">
            <input type="search" class="input" name="search" placeholder="キーワード検索">
            <a class="button is-info">
              <i class="fa fa-search"></i>検索
            </a>
          </div>
        </span>
        <span class="nav-item">
          <a href="#" class="fa fa-user">ログイン</a>
        </span>
      </div>
    </header>

    <div class="hero is-info is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">CASAREAL</h1>
          <h2 class="subtitle">@casareal-ls</h2>
        </div>
      </div>
    </div>

    <section class="level">
      <div class="level-left"></div>
      <div class="level-right">
        <div class="level-item tabs">
          <ul>
            <li class="is-active">
              <a>最近の一言</a>
            </li>
            <li>
              <a>古い一言</a>
            </li>
            <li>
              <a>コメント付き</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="level-right">
        <div class="level-item">
          <a class="button is-greylight">フォロー</a>
        </div>
      </div>
    </section>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.4/css/bulma.css">
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
