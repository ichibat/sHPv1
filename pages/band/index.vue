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

    <section class="hero">
      <figure class="image">
        <img src="~/assets/mainImage.jpg">
      </figure>
    </section>

    <h1
      class="is-size-5 has-text-primary"
    >練馬およびその周辺地域の在宅医療-すみれホームケアクリニック-患者様の「おうちで過ごしたい」を医師が24時間サポートします．</h1>
    <h2 class="is-size-5">電話での相談は随時受け付けております．TEL03-6904-5828</h2>

    <section class="section">
      <div class="container has-text-centered">
        <h2 class="title">在宅医療のすすめ</h2>
        <p>
          &nbsp;近年様々な病気が医学の進歩で克服されましたが、その結果継続的に治療を受け人生を過ごす方が少なくありません。認知症、脳卒中などの神経疾患や、がんが代表的ですが、患者さんにとっては治療が生活や人生の全てではなく、できれば住み慣れた家で生活したいいと考える方も増えています。
          <br>&nbsp;こうした変化の背景として、従来入院でしかできなかった治療が在宅でもできるようになったことが挙げられます。
          更に自分の生活のペースを変えずに家族に囲まれた環境で療養することで、生活の質の向上も期待できます。
          当院では、通院が困難な方や在宅での療養を希望される方に定期的な訪問診療をすることにより、最適な医療を提供したいと考えています。
          <br>&nbsp;電話(
          <span class="has-text-info">03-6904-5828</span>)，メールでのご相談は随時受け付けておりますので，お気軽にご連絡ください．
        </p>

        <h2 class="title">お知らせ</h2>
        <p>&nbsp;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Neque quae accusantium consequuntur. Eius ipsa maiores error? Sunt, tempore. Totam aut deserunt dolores labore minima molestiae perspiciatis perferendis quasi, illum eaque accusamus a quisquam quibusdam!</p>

        <div class="columns is-centered" style="padding: 2rem">
          <div class="column">
            <div class="card">
              <div class="card-image">
                <figure class="image is-2by1">
                  <img
                    src="https://images.pexels.com/photos/167635/pexels-photo-167635.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                    alt="Placeholder image"
                  >
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="media-content">
                    <p class="title is-4">John Smith</p>
                    <p class="subtitle is-6">@johnsmith</p>
                  </div>
                </div>

                <div class="content">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                  <a>@bulmaio</a>.
                  <a href="#">#css</a>
                  <a href="#">#responsive</a>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <div class="card-image">
                <figure class="image is-2by1">
                  <img
                    src="https://images.pexels.com/photos/167635/pexels-photo-167635.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                    alt="Placeholder image"
                  >
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="media-content">
                    <p class="title is-4">John Smith</p>
                    <p class="subtitle is-6">@johnsmith</p>
                  </div>
                </div>

                <div class="content">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                  <a>@bulmaio</a>.
                  <a href="#">#css</a>
                  <a href="#">#responsive</a>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <div class="card-image">
                <figure class="image is-2by1">
                  <img
                    src="https://images.pexels.com/photos/167635/pexels-photo-167635.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                    alt="Placeholder image"
                  >
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="media-content">
                    <p class="title is-4">John Smith</p>
                    <p class="subtitle is-6">@johnsmith</p>
                  </div>
                </div>

                <div class="content">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                  <a>@bulmaio</a>.
                  <a href="#">#css</a>
                  <a href="#">#responsive</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container has-text-centered">
        <h2 class="title">Tour Dates</h2>

        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
        </div>

        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image">
                <img
                  src="https://images.pexels.com/photos/374710/pexels-photo-374710.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                >
              </figure>
              <p class="title">New York</p>
              <p class="subtitle">Fri 27 Nov 2016</p>
              <a class="button">Buy Tickets</a>
            </article>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container has-text-centered">
        <h2 class="title">Contact</h2>

        <form>
          <div class="field is-horizontal">
            <div class="field-body">
              <div class="field">
                <p class="control has-icons-left">
                  <input class="input" type="text" placeholder="Name">
                  <span class="icon is-small is-left">
                    <i class="fas fa-user"></i>
                  </span>
                </p>
              </div>
              <div class="field">
                <p class="control has-icons-left has-icons-right">
                  <input class="input" type="email" placeholder="Email">
                  <span class="icon is-small is-left">
                    <i class="fas fa-envelope"></i>
                  </span>
                </p>
              </div>
            </div>
          </div>

          <div class="field is-horizontal">
            <div class="field-body">
              <div class="field">
                <div class="control">
                  <textarea class="textarea" placeholder="Message us"></textarea>
                </div>
              </div>
            </div>
          </div>

          <div class="field is-horizontal">
            <div class="field-body">
              <div class="field">
                <div class="control">
                  <button class="button is-primary">Send message</button>
                </div>
              </div>
            </div>
          </div>
        </form>
      </div>
    </section>

    <footer class="footer">
      <div class="container">
        <div class="content has-text-centered">
          <p>
            <a href>
              <i class="fab fa-facebook-square fa-2x"></i>
            </a>
            <a href>
              <i class="fab fa-twitter-square fa-2x"></i>
            </a>
            <a href>
              <i class="fab fa-instagram fa-2x"></i>
            </a>
            <a href>
              <i class="fab fa-snapchat fa-2x"></i>
            </a>
          </p>
          <p>
            <a href="https://bulma.io">
              <img
                src="https://bulma.io/images/made-with-bulma.png"
                alt="Made with Bulma"
                width="128"
                height="24"
              >
            </a>
          </p>
        </div>
      </div>
    </footer>
    <script src="../js/bulma.js"></script>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
