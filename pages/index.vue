<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="./">
        <img
          src="assets/img/brand.png"
          width="30"
          height="30"
          class="d-inline-block align-top mr-1"
          alt="Honoka"
        />
        Honoka
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbar"
        aria-controls="navbar"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbar">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="./"
              >Top <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Live demo
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="./bootstrap-ja.html"
                >Japanese Page</a
              >
              <a class="dropdown-item" href="./bootstrap.html">English Page</a>
            </div>
          </li>
          <li class="nav-item">
            <a
              class="nav-link"
              href="http://github.com/windyakin/Honoka/releases"
              >Download</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="http://github.com/windyakin/Honoka/wiki"
              >Wiki</a
            >
          </li>
        </ul>
        <!-- <div class="form-inline my-2 my-lg-0">
            </div> -->
      </div>
    </div>
  </nav>

  <div class="jumbotron special">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 d-xl-block d-none">
          <div class="honoka"></div>
        </div>
        <div class="col-xl-8 outline text-xl-left text-center">
          <div class="display-3 copy">
            <span class="d-inline-block">その Bootstrap は､</span><br />
            <span class="d-inline-block">日本語も</span
            ><span class="d-inline-block"><u>美しく</u></span
            ><br />
            <span class="d-inline-block">表示されて</span
            ><span class="d-inline-block">ますか？</span>
          </div>
          <p class="lead mt-2">
            Honoka は日本語も美しく表示できる Bootstrap テーマです
          </p>
          <hr />
          <ul class="download list-inline">
            <li class="list-inline-item">
              <a
                href="//github.com/windyakin/Honoka/releases"
                class="btn btn-honoka btn-lg last-release-download-link"
                ><i class="fab fa-github-alt"></i> Download from GitHub</a
              >
            </li>
            <li class="list-inline-item">
              <a href="/bootstrap-ja.html" class="btn btn-primary btn-lg"
                ><i class="fa fa-play-circle"></i> Live Demo</a
              >
            </li>
          </ul>
          <div class="basedon small">
            Last version v<span class="last-version"></span> ・ Based on
            <a href="http://getbootstrap.com/">Bootstrap</a> v<span
              class="base-version"
            ></span>
          </div>
        </div>
      </div>
    </div>
  </div>

  <aside class="social">
    <div class="social-button">
      <ul>
        <li>
          <iframe
            src="https://ghbtns.com/github-btn.html?user=windyakin&repo=Honoka&type=star&count=true"
            frameborder="0"
            scrolling="0"
            width="90px"
            height="20px"
          ></iframe>
        </li>
        <li>
          <a
            href="https://twitter.com/share"
            class="twitter-share-button"
            data-lang="ja"
            data-dnt="true"
            >ツイート</a
          >
        </li>
        <li>
          <div
            class="fb-like"
            data-href="http://honokak.osaka/"
            data-layout="button_count"
            data-action="like"
            data-show-faces="false"
            data-share="false"
          ></div>
        </li>
        <li>
          <a
            href="http://b.hatena.ne.jp/entry/"
            class="hatena-bookmark-button"
            data-hatena-bookmark-layout="standard-balloon"
            data-hatena-bookmark-lang="ja"
            title="このエントリーをはてなブックマークに追加"
            ><img
              src="https://b.st-hatena.com/images/entry-button/button-only@2x.png"
              alt="このエントリーをはてなブックマークに追加"
              width="20"
              height="20"
              style="border: none"
          /></a>
        </li>
      </ul>
    </div>
  </aside>

  <section class="section section-default point">
    <div class="container">
      <div class="row">
        <div class="col-12 subtitle">
          <h2>HonokaはオリジナルBootstrapテーマです</h2>
          <p class="lead">
            HonokaはBootstrapテーマの一つですが、以下の特徴を持っています。
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-3 col-sm-6 point-box">
          <div class="point-circle start">
            <i class="fa fa-check"></i>
          </div>
          <div class="point-description">
            <h4>Easy to Start</h4>
            <p>
              HonokaはBootstrapを元に製作されているため、非常に高い互換性を持っています。マークアップに関する規約はほとんど変わりません。
            </p>
          </div>
        </div>
        <div class="col-md-3 col-sm-6 point-box">
          <div class="point-circle replace">
            <i class="fa fa-sync-alt"></i>
          </div>
          <div class="point-description">
            <h4>Replace Bootstrap</h4>
            <p>
              既にBootstrapを使って作成したウェブサイトがある場合は、CSSを置き換えるだけで簡単にHonokaを利用できます。
            </p>
          </div>
        </div>
        <div class="col-md-3 col-sm-6 point-box">
          <div class="point-circle compass">
            <i class="fab fa-github-alt"></i>
          </div>
          <div class="point-description">
            <h4>Open Source</h4>
            <p>
              Honokaを構成するファイルは全て公開されています。変数の定義ファイルを変更することで自分好みの設定に変更することも可能です。
            </p>
          </div>
        </div>
        <div class="col-md-3 col-sm-6 point-box">
          <div class="point-circle japanese">
            <span class="icon-jp"></span>
          </div>
          <div class="point-description">
            <h4>Optimized Japanese</h4>
            <p>
              Bootstrapでは考慮されていない日本語のフォント指定やウェイトの変更を行っているので、美しく日本語を表示できます。
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section section-inverse getting-started">
    <div class="container">
      <div class="row">
        <div class="col-12 subtitle">
          <h2>さあ、はじめましょう。</h2>
          <p class="lead">導入はとっても簡単です</p>
        </div>
      </div>
      <div class="row my-3">
        <div class="col-12 text-center">
          <div class="form-group">
            <a
              href="//github.com/windyakin/Honoka/releases"
              class="btn btn-primary btn-lg last-release-download-link"
              ><i class="fas fa-file-archive fa-lg mr-2"></i> Download from
              GitHub</a
            >
            <p class="form-text text-muted">
              <small
                >Last version v<span class="last-version"></span> ・
                <a href="//github.com/windyakin/Honoka/blob/master/LICENSE"
                  >MIT License</a
                ></small
              >
            </p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 text-center my-3">
          <h3>
            <a href="https://www.npmjs.com/package/bootstrap-honoka"
              ><img
                src="assets/img/npm-logo.png"
                alt="npm"
                class="img-fluid package-system-logo"
            /></a>
          </h3>
          <div class="input-group input-group-lg">
            <input
              type="text"
              class="form-control border-secondary"
              id="npm-install-command"
              value="npm install --save bootstrap-honoka"
              onclick="this.select();"
            />
            <span class="input-group-append">
              <button
                type="button"
                class="btn btn-light border-secondary"
                data-clipboard-target="#npm-install-command"
              >
                <i class="fa fa-clipboard"></i>
              </button>
            </span>
          </div>
          <div>
            <small class="form-text text-muted"
              ><a href="https://www.npmjs.com/package/bootstrap-honoka"
                >npmjs.com</a
              >
              / v3.3.7-a 以降から対応</small
            >
          </div>
        </div>
        <div class="col-md-6 text-center my-3">
          <h3>
            <img
              src="assets/img/bower-logo.png"
              alt="Bower"
              class="img-fluid package-system-logo"
            />
            Bower
          </h3>
          <div class="input-group input-group-lg">
            <input
              type="text"
              class="form-control border-secondary"
              id="bower-install-command"
              value="bower install --save $(node -e &#34;$(curl -fsSL https://cdn.honokak.osaka/last.js)&#34; windyakin Honoka)"
              onclick="this.select();"
            />
            <span class="input-group-append">
              <button
                type="button"
                class="btn btn-light border-secondary"
                data-clipboard-target="#bower-install-command"
              >
                <i class="fa fa-clipboard"></i>
              </button>
            </span>
          </div>
          <div>
            <small class="form-text text-muted">v3.3.5-c 以降から対応</small>
          </div>
        </div>
      </div>
      <div class="row mt-3">
        <div class="col-12 text-center">
          <p>
            使い方やファイルの説明など、詳しくは
            <a href="//github.com/windyakin/Honoka#readme">README</a> または
            <a href="//github.com/windyakin/Honoka/wiki">Wiki</a>
            をご確認ください
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="section section-inverse avaliable-webpack d-none">
    <div class="container">
      <div class="row">
        <div class="col-12 subtitle">
          <h2>Available on Framework!</h2>
          <p class="lead">
            Honokaは様々なパッケージマネージャからも利用することができます
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 text-center">
          <h3>
            <a href="https://www.npmjs.com/package/bootstrap-honoka"
              ><img
                src="assets/img/npm-logo.png"
                alt="npm"
                class="img-fluid package-system-logo"
            /></a>
          </h3>
          <div class="input-group input-group-lg">
            <input
              type="text"
              class="form-control"
              id="npm-install-command"
              value="npm install --save bootstrap-honoka"
              onclick="this.select();"
            />
            <span class="input-group-append">
              <button
                type="button"
                class="btn btn-secondary"
                data-clipboard-target="#npm-install-command"
              >
                <i class="fa fa-clipboard"></i>
              </button>
            </span>
          </div>
          <div>
            <small class="form-text text-muted"
              ><a href="https://www.npmjs.com/package/bootstrap-honoka"
                >npmjs.com</a
              >
              / v3.3.7-a 以降から対応</small
            >
          </div>
        </div>
        <div class="col-md-6 text-center">
          <h3>
            <img
              src="assets/img/bower-logo.png"
              alt="Bower"
              class="img-fluid package-system-logo"
            />
            Bower
          </h3>
          <div class="input-group input-group-lg">
            <input
              type="text"
              class="form-control"
              id="bower-install-command"
              value="bower install --save $(node -e &#34;$(curl -fsSL https://cdn.honokak.osaka/last.js)&#34; windyakin Honoka)"
              onclick="this.select();"
            />
            <span class="input-group-append">
              <button
                type="button"
                class="btn btn-secondary"
                data-clipboard-target="#bower-install-command"
              >
                <i class="fa fa-clipboard"></i>
              </button>
            </span>
          </div>
          <div>
            <small class="form-text text-muted">v3.3.5-c 以降から対応</small>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section section-default used-by">
    <div class="container">
      <div class="row">
        <div class="col-12 subtitle">
          <h2>Honokaを使って作られたウェブサイト</h2>
          <p class="lead">
            HonokaやそのForkテーマで構築されたウェブサイトを紹介します
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-4">
          <div class="card my-3">
            <a href="https://proconist.net/"
              ><img
                src="//cdn.honokak.osaka/assets/img/proconist.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h5 class="card-title m-0">Proconist.net</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card my-3">
            <a href="http://sugoi.windyakin.net/"
              ><img
                src="//cdn.honokak.osaka/assets/img/sugoi.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h5 class="card-title m-0">この高専がすごい！</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card my-3">
            <a href="http://yashihei.net/"
              ><img
                src="//cdn.honokak.osaka/assets/img/yashihei.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h5 class="card-title m-0">yashihei.net</h5>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-4">
          <div class="card my-3">
            <a href="http://sysken.org/advent2015/"
              ><img
                src="//cdn.honokak.osaka/assets/img/sysken.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h5 class="card-title m-0">SYSKEN Advent Calendar</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card my-3">
            <a href="http://timers-inc.com/"
              ><img
                src="//cdn.honokak.osaka/assets/img/timers-inc.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h5 class="card-title m-0">TIMERS Inc</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card my-3">
            <a href="http://ost.procon-online.net/"
              ><img
                src="//cdn.honokak.osaka/assets/img/ost.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h5 class="card-title m-0">PROCON O.S.T. Project</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section section-inverse fork">
    <div class="container">
      <div class="row">
        <div class="col-12 subtitle">
          <h2>HonokaのForkテーマ</h2>
          <p>Honokaをベースにして作られた他のBootstrapテーマ</p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6">
          <div class="card my-3">
            <a href="//ysakasin.github.io/Umi/"
              ><img
                src="//cdn.honokak.osaka/assets/img/umi.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h4 class="card-title">Umi</h4>
              <p>
                "Umi"は"Honoka"に<a href="https://bootswatch.com/flatly/"
                  >Bootswatch Flatly</a
                >の配色を適用したテーマです。
              </p>
              <div>
                <a href="//ysakasin.github.io/Umi/" class="btn btn-primary"
                  >Umiの特設ページ <i class="fa fa-external-link-alt"></i
                ></a>
                <a
                  href="//github.com/ysakasin/Umi"
                  class="btn btn-outline-secondary"
                  >Umi on GitHub <i class="fab fa-github-alt"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="card my-3">
            <a href="http://nico.kubosho.com/"
              ><img
                src="//cdn.honokak.osaka/assets/img/nico.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h4 class="card-title">Nico</h4>
              <p>"Nico"は"Honoka"にピンク系の配色を適用したテーマです。</p>
              <div>
                <a href="http://nico.kubosho.com/" class="btn btn-primary"
                  >Nicoの特設ページ <i class="fa fa-external-link-alt"></i
                ></a>
                <a
                  href="//github.com/kubosho/Nico"
                  class="btn btn-outline-secondary"
                  >Nico on GitHub <i class="fab fa-github-alt"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="offset-md-3 col-md-6">
          <div class="card my-3">
            <a href="//rinhoshizo.la/"
              ><img
                src="//cdn.honokak.osaka/assets/img/rin.png"
                class="card-img-top"
            /></a>
            <div class="card-body text-center">
              <h4 class="card-title">Rin</h4>
              <p>"Rin"は"Honoka"を元にしたMaterial Design風のテーマです。</p>
              <div>
                <a href="//rinhoshizo.la/" class="btn btn-primary"
                  >Rinの特設ページ <i class="fa fa-external-link-alt"></i
                ></a>
                <a
                  href="//github.com/raryosu/Rin"
                  class="btn btn-outline-secondary"
                  >Rin on GitHub <i class="fab fa-github-alt"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section section-default featured">
    <div class="container">
      <div class="row">
        <div class="col-12 subtitle">
          <h2>Honoka has been featured on</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-12 text-center">
          <ul class="list-inline featured-list">
            <li class="list-inline-item">
              <a
                href="http://www.moongift.jp/2015/06/honoka-%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%82%82%E7%B6%BA%E9%BA%97%E3%81%AB%E8%A1%A8%E7%A4%BA%E3%81%A7%E3%81%8D%E3%82%8Bbootstrap%E3%83%86%E3%83%BC%E3%83%9E/"
                ><img
                  src="http://cdn.honokak.osaka/assets/img/moongift.png"
                  alt="MOONGIFT"
              /></a>
            </li>
            <li class="list-inline-item">
              <a
                href="http://coliss.com/articles/build-websites/operation/work/bootstrap-theme-honoka.html"
                ><img
                  src="http://cdn.honokak.osaka/assets/img/coliss.png"
                  alt="コリス"
              /></a>
            </li>
            <li class="list-inline-item">
              <a href="http://stocker.jp/diary/web-news-may2015/"
                ><img
                  src="http://cdn.honokak.osaka/assets/img/stockerjp.png"
                  alt="Stocker.jp / diary"
              /></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <div class="social-button">
    <ul>
      <li>
        <iframe
          src="https://ghbtns.com/github-btn.html?user=windyakin&repo=Honoka&type=star&count=true"
          frameborder="0"
          scrolling="0"
          width="90px"
          height="20px"
        ></iframe>
      </li>
      <li>
        <a
          href="https://twitter.com/share"
          class="twitter-share-button"
          data-lang="ja"
          data-dnt="true"
          >ツイート</a
        >
      </li>
      <li>
        <div
          class="fb-like"
          data-href="http://honokak.osaka/"
          data-layout="button_count"
          data-action="like"
          data-show-faces="false"
          data-share="false"
        ></div>
      </li>
      <li>
        <a
          href="http://b.hatena.ne.jp/entry/"
          class="hatena-bookmark-button"
          data-hatena-bookmark-layout="standard-balloon"
          data-hatena-bookmark-lang="ja"
          title="このエントリーをはてなブックマークに追加"
          ><img
            src="https://b.st-hatena.com/images/entry-button/button-only@2x.png"
            alt="このエントリーをはてなブックマークに追加"
            width="20"
            height="20"
            style="border: none"
        /></a>
      </li>
    </ul>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-12 text-center copyright">&copy; 2015 Honoka</div>
    </div>
  </div>
</template>
