<template>
  <div>
    <div class="newsblog">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md">
            <h2>NEWS&BLOG</h2>
            <div class="halfborder"></div>
            <h3>住まいづくりは幸せづくり</h3>
            <p>
              地域の皆様と共に歩んでまいりました。
              <br />
              決して派手ではないけれど、心から信頼できる建築設計会社であり続けたい。
              <br />
              今後も地域密着だからこそできる迅速な対応でお客様の暮らしを支えます。
            </p>
          </div>
          <div class="col-md">
            <div>
              <ul>
                <li>
                  <nuxt-link to="">新年のご挨拶申し上げます</nuxt-link>
                </li>
                <div class="halfborderli"></div>
                <li>
                  <nuxt-link to="">年末年始の休業日ご案内</nuxt-link>
                </li>
                <div class="halfborderli"></div>
                <li>
                  <nuxt-link to="">オフィシャルサイトを開設しました</nuxt-link>
                </li>
                <div class="halfborderli"></div>
                <li>
                  <nuxt-link to="">お盆期間中の休業日ご案内</nuxt-link>
                </li>
                <div class="halfborderli"></div>
                <li>
                  <nuxt-link to="">GW期間中の休業日ご案内</nuxt-link>
                </li>
                <div class="halfborderli"></div>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-md footerbtn1">
        <nuxt-link to="">
          <h4>COMPANY</h4>
          <p>家づくりの進め方から会社概要まで</p>
        </nuxt-link>
      </div>
      <div class="col-md footerbtn2">
        <nuxt-link to="">
          <h4>TEL:096-201-3353</h4>
          <p>お電話でのお問い合わせはこちら</p>
        </nuxt-link>
      </div>
    </div>
    <footer>
      <div class="footercontainer">
        <div class="footeritem newsleft">
          <div class="footersentence">
            <nuxt-link to=""> NEWS<span class="align-middle">ニュース</span> </nuxt-link>
          </div>
          <div class="footersentence">
            <nuxt-link to=""> WORKS<span class="align-middle">作品一覧</span> </nuxt-link>
          </div>
          <div class="footersentence">
            <nuxt-link to="">
              PROFILE<span class="align-middle">プロフィール</span>
            </nuxt-link>
          </div>
          <div class="footersentence">
            <nuxt-link to="">
              FOR CLIENT<span class="align-middle">業務内容やフローなど</span>
            </nuxt-link>
          </div>
          <div class="footersentence">
            <nuxt-link to=""> FLOW<span class="align-middle">ご依頼の流れ</span> </nuxt-link>
          </div>
          <div class="footersentence">
            <nuxt-link to="">
              PRIVACY POLICY<span class="align-middle"
                >プライバシーポリシー</span
              >
            </nuxt-link>
          </div>
        </div>
        <div class="footeritem newsright">
          <div>
            <nuxt-link to="">
              <img class="footerimg" src="/images/footerLogo.jpg" alt="" />
            </nuxt-link>
          </div>
          <div class="question">
            <nuxt-link to="">
              <span>
                <i class="far fa-envelope"></i>
              </span>
              お問い合わせ
            </nuxt-link>
          </div>
          <div>
            <div class="nummap">
              <nuxt-link to="">
                <span>
                  <i class="fas fa-phone"></i>
                </span>
                096-201-3353
              </nuxt-link>
            </div>
            <div class="nummap">
              <span>
                <i class="fas fa-map-marker-alt"></i>
              </span>
              〒861-8006 熊本市北区龍田3丁目29-3
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="sustainablelogo">
          <nuxt-link to="">
            <img src="/images/footer_logo.jpg" alt="" />
          </nuxt-link>
        </div>
        <div class="sns flex-row">
          <nuxt-link to="">
            <i class="fab fa-instagram"></i>
          </nuxt-link>
          <nuxt-link to="">
            <i class="fab fa-facebook"></i>
          </nuxt-link>
        </div>
        <p class="copyrights">
          <small>
            Copyright © Sustainable Co., Ltd. All rights reserved.
            <br class="bo" />
            Design by
            <nuxt-link to=""> Higashikaigan Inc. </nuxt-link>
          </small>
        </p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.container-fluid {
  max-width: 1600px;
  font-family: sans-serif;
  line-height: 2em;
  letter-spacing: 0.04em;
}
.newsblog {
  background-image: url("/images/top_news_bg.jpg");
  background-size: cover;
  background-position: center;
  padding: 50px 0;
  color: white;
}
.newsblog h2 {
  font-family: serif;
  font-size: 30px;
  padding-bottom: 30px;
}
.halfborder {
  width: 50px;
  border-bottom: 1px solid white;
  margin-bottom: 40px;
}
.newsblog h3 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 18px;
  padding-bottom: 20px;
}
li a {
  color: white;
}
.newsblog ul {
  list-style-type: none;
  padding-top: 60px;
  padding-left: 0;
}
.newsblog li {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 15px;
  padding-bottom: 15px;
}
.halfborderli {
  width: 20px;
  border-bottom: 1px solid white;
  margin-bottom: 15px;
}
.footercontainer {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.footeritem {
  width: 100%;
}
.footerbtn1 {
  text-align: center;
  padding: 50px;
  background-color: #313131;
  transition: all 0.7s;
}
.footerbtn1:hover{
  opacity: 0.5;
}
.footerbtn1 a {
  color: white;
}
.footerbtn1 h4 {
  font-size: 28px;
  font-weight: 400;
}
.footerbtn1 p {
  font-size: 13px;
}
.footerbtn2 a {
  color: white;
}
.footerbtn2 h4 {
  font-size: 28px;
  font-weight: 400;
}
.footerbtn2 p {
  font-size: 13px;
}
.footerbtn2 {
  text-align: center;
  padding: 50px;
  background-color: #1a1a1a;
  transition: all 0.7s;
}
.footerbtn2:hover{
  opacity: 0.5;
}
footer {
  max-width: 1400px;
  margin: 0 auto;
}

.footerimg {
  width: 100%;
}
.newsleft {
  margin: 40px 30px;
  padding: 40px 30px;
  border-top: 1px solid #333;
  border-bottom: 1px solid #333;
}
.newsright {
  margin: 0 25px;
}
.footersentence a {
  color: #666;
  font-family: serif;
  line-height: 1.5em;
  font-size: 23px;
  word-spacing: 0.4;
}
.footersentence span {
  color: #666;
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.5em;
  font-size: 10px;
  margin-left: 15px;
}

.question {
  text-align: center;
  margin: 20px 0;
  padding: 10px 0;
  background-color: black;
}
.question a {
  color: white;
  font-size: 13px;
}

.sustainablelogo {
  margin: 35px 0;
  text-align: center;
}
.sns {
  text-align: center;
}
.sns i {
  color: #666;
  font-size: 28px;
  padding: 0 15px;
}
.nummap {
  font-family: Arial;
  font-size: 14px;
}
.nummap a {
  color: black;
}
.copyrights {
  font-family: arial;
  color: #333;
  font-size: 15px;
  margin: 30px 0;
}
.copyrights a {
  color: #333;
}
a:hover{
  text-decoration: none;
}
@media screen and (min-width: 768px) {
  .newsblog {
    padding: 100px 120px;
  }
  .newsblog ul {
    padding-top: 0px;
  }
  .footerbtn1,
  .footerbtn2 {
    padding: 80px;
  }
  .footercontainer {
    margin: 120px 60px 0px;
    border-top: 1px solid #333;
    padding: 20px;
  }
  .footeritem {
    width: 50%;
  }
  .newsleft {
    margin: 0px;
    padding: 20px 100px;
    border-top: 0px solid #333;
    border-bottom: 0px solid #333;
    border-right: 1px solid #333;
  }
  .newsright {
    margin: 0px;
    padding: 20px 100px;
    align-self: center;
  }
  .bo {
    display: none;
  }
}
</style>