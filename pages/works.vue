<template>
  <div>
    <section class="sub_header">
      <div class="header_image">
        <div class="subheader">
          <nuxt-link to="/">
            <img src="/images/sec_logo.png" alt="" />
          </nuxt-link>
        </div>
        <div class="subquetion">
          <nuxt-link to="">
            <span>
              <i class="far fa-envelope"></i>
            </span>
            お問い合わせ
          </nuxt-link>
        </div>
      </div>
      <div class="header_nav">
        <div class="topsentence">
          <h1>WORKS</h1>
        </div>
        <div class="topline">
          <nuxt-link to="/"> TOP </nuxt-link>
          <nuxt-link to="/works"> WORKS </nuxt-link>
          <nuxt-link to=""> PROFILE </nuxt-link>
          <nuxt-link to=""> FOR CLIENT </nuxt-link>
          <nuxt-link to=""> FLOW </nuxt-link>
        </div>
      </div>
    </section>
    <section class="container-fluid">
      <div class="worklist">
        <h2>施工実績</h2>
        <p>
          将来を見据えた設計、普遍的なデザイン、経年変化が楽しめる素材、快適に過ごせる性能、安心して暮らせる構造。
          <br />
          すべての要素が調和した住まい・空間をお届けします。
        </p>
      </div>
    </section>
    <section class="works_flex">
      <div class="workscontents-list">
        <img src="/images/mon.jpg" alt="" />
        <div class="worktext">
          <h3>モン・プチパレ(M様アトリエ兼美術館)</h3>
          <p>「⻑年の夢を叶えたプチ美術館」</p>
          <div>
            <dl>
              <dt>種別</dt>
              <dd>新築 / アトリエ・美術館</dd>
            </dl>
            <dl>
              <dt>構造</dt>
              <dd>⽊造</dd>
            </dl>
            <dl>
              <dt>建築地</dt>
              <dd>熊本県阿蘇郡南阿蘇村</dd>
            </dl>
            <div class="borderbo"></div>
          </div>
        </div>
      </div>
      <div class="workscontents-list">
        <img src="/images/Ksama.jpg" alt="" />
        <div class="worktext">
          <h3>k様邸</h3>
          <p>「パートナーや⼤好きなネコとのんびり暮らせる家」</p>
          <div>
            <dl>
              <dt>種別</dt>
              <dd>新築 / ⼾建て住宅</dd>
            </dl>
            <dl>
              <dt>構造</dt>
              <dd>⽊造</dd>
            </dl>
            <dl>
              <dt>建築地</dt>
              <dd>熊本県熊本市東区⼾島⻄</dd>
            </dl>
            <div class="borderbo"></div>
          </div>
        </div>
      </div>
      <div class="workscontents-list">
        <img src="/images/funazaki.jpg" alt="" />
        <div class="worktext">
          <h3>船崎邸</h3>
          <p>「経年変化を楽しむ家」</p>
          <div>
            <dl>
              <dt>種別</dt>
              <dd>新築 / ⼾建て住宅</dd>
            </dl>
            <dl>
              <dt>構造</dt>
              <dd>⽊造</dd>
            </dl>
            <dl>
              <dt>建築地</dt>
              <dd>熊本県熊本市北区⿓⽥</dd>
            </dl>
            <div class="borderbo"></div>
          </div>
        </div>
      </div>
    </section>
    <AppFooter />
    <Appmodal />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container-fluid {
  max-width: 1410px;
}
.sub_header {
  background-color: #f1f1f1;
}
.header_image {
  display: flex;
}
.header_nav {
  display: flex;
  background-color: #fff;
  margin-left: 46px;
  padding: 16px 42px;
}

.subheader {
  height: 24vw;
  width: 50%;
}
.subheader img {
  margin-top: 26px;
  margin-left: 46px;
  width: 54%;
}

.subquetion {
  text-align: right;
  padding-right: 105px;
  width: 50%;
}
.subquetion a {
  display: block;
  padding: 20px 20px;
  font-size: 15px;
}
.subquetion a {
  color: black;
}
.topsentence {
  width: 50%;
}
.topsentence h1 {
  font-family: arial;
  font-weight: bold;
  font-size: 33px;
  line-height: 1.4;
  width: 50%;
}
.topline {
  width: 50%;
  text-align: right;
  align-self: center;
}
.topline a {
  color: black;
  padding-left: 20px;
}
.worklist {
  text-align: center;
  padding: 50px 0;
}
.worklist h2 {
  font-family: source-han-serif-japanese, serif;
  font-weight: 500;
  font-style: normal;
  font-size: 21px;
  padding-bottom: 40px;
}
p {
  font-family: noto-sans-cjk-jp, sans-serif, "源ノ角ゴシック Regular",
    源ノ角ゴシック, 游ゴシック体, "Yu Gothic", YuGothic, "Helvetica Neue",
    Helvetica, Arial, sans-serif;
  font-weight: 500;
  font-style: normal;
  font-size: 15px;
}
.works_flex {
  display: flex;
  flex-wrap: wrap;
  max-width: 1400px;
  margin: 0 auto;
}
.workscontents-list {
  width: 50%;
  padding: 10px 30px;
}
.workscontents-list img {
  width: 100%;
}
.worktext {
  padding: 10px 0 40px;
}
.worktext h3 {
  font-family: source-han-serif-japanese, serif;
  font-style: normal;
  font-size: 24px;
  font-weight: 600;
  padding: 30px 0;
  margin: 0;
}
dl {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  border-top: 1px dotted #ddd;
  padding: 20px 0;
  margin: 0;
}
dt {
  width: 30%;
}
dd {
  width: 70%;
  margin: 0;
}
.borderbo {
  border-top: 1px dotted #ddd;
}


@media screen and (max-width: 768px) {
  .subquetion {
    display: none;
  }
  .topline {
    display: none;
  }
  .header_nav {
    display: flex;
    background-color: #fff;
    margin-left: 46px;
    padding: 16px 42px;
  }

  .topsentence h1 {
    font-family: arial;
    font-weight: bold;
    font-size: 33px;
    line-height: 1.4;
  }
  .subheader {
    width: 100%;
  }
  .subheader img {
    margin-top: 17px;
    margin-left: 21px;
    width: 68%;
  }
  .workscontents-list {
    width: 100%;
    padding: 10px 30px;
  }
}
</style>