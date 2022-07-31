<template>
  <div>
    <header class="header">
      <div class="headerh1">
        <h1>
          SUSTAINABLE
          <br />
          ARCHITECT
          <br />
          LABORATORY
        </h1>
      </div>
      <div class="headerimg">
        <img src="/images/icon.png" alt="" />
      </div>
    </header>
    <main>
      <div class="container-fluid">
        <div class="message">
          <h2>MESSAGE</h2>
          <div class="messagepos row">
            <div class="col-md order-md-2 messagevertical">
              地域や気候風土に寄り添った建築を
              <br />
              丁寧にデザインし、
              <br />
              住み継いで頂けるような家づくりを
            </div>
            <div class="col-md order-md-1 messageleft">
              <p>
                近年、日本では住宅の耐用年数は約30年と言われ続けています。
                <br />
                それはスクラップ&ビルドという高度経済成長以降の悪しき慣例慣習が影響していると思われます。
                <br />
                しかし伝統的な日本家屋や、古き物の価値が認められる欧州のように、気候風土に合った建物に手を加えながら、代々住み継いでいく事が住宅建築本来のあり方ではないかと考えます。
                <br />
                <br />
                そこで、「持続可能な住まいをデザインする」という企業理念を掲げ、住む人はもちろん、その地域や気候風土に寄り添った建築を丁寧にデザインし、将来にわたって住み継いで頂けるような家づくりを目指します。
              </p>
              <div class="sustainablelogo">
                <img src="/images/top_logo01.png" alt="" />
              </div>
            </div>
            <div class="messageusuimg">
              <img src="/images/text_message.png" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="contents">
          <div class="contentsimage">
            <img src="images/mainvisual01.jpg" alt="" />
            <h2>
              SUSTAINABLE
              <br />
              ARCHITECT
              <br />
              LABORATORY
            </h2>
          </div>
          <div class="row contentsen">
            <div class="col-md contentsen2">
              <h3>
                誠心誠意、家づくりを
                <br />
                行うことをお約束します。
              </h3>
            </div>
            <div class="col-md">
              <p>
                1.安心、安全、光や風をデザインし、快適性、耐震や耐久性を持続させる。
                <br />
                2.度々変わる国の基準に振り回されない、気候風土に根差したデザインを深く考え、本質的な建物の断熱、省エネ、気密性を持続させる。
                <br />
                3.将来にわたり、家族構成の変化や身体的な変化に対応出来るプラン、構造をデザインし、可変性を持続させる。
                <br />
                4.長年、住み継いでいくためのデザインを考え、設備機器の交換や修繕、内装や外装のリノベーションのしやすさを持続させる。
                <br />
                5.お客様や地域に寄り添ったデザイン、お施主様とのお付き合いを生涯にわたり持続させる。
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="forclient">
        <div class="forclientitem1">
          <nuxt-link to="">
            <img class="forclientimg" src="/images/top_img02.jpg" alt="" />
          </nuxt-link>
        </div>
        <div class="forclientitem2 forclient2">
          <h3>
            FOR
            <br />
            CLIENT
          </h3>
          <p>
            ⽇々の暮らしにおいて必要不可⽋ではないもの中に、その⼈・家族にとってとても⼤切なものが
            あったりします。
            <br />
            その⼤切な事柄や想いをひとつずつ集めて、⼈・家族にとって必要不可⽋な『家』を作り上げていく事をお⼿伝い致します。
          </p>
          <div class="buttonde">
            <button>詳しくはこちら</button>
          </div>
        </div>
      </div>
      <div class="profileflex">
        <div class="profileitem profilelogo">
          <img class="profileimg" src="/images/top_img03.jpg" alt="" />
          <div class="profilebw"><span>PRO</span>FILE</div>
        </div>
        <div class="profileitem profileh2">
          <h2>持続可能な住まいをデザインする</h2>
          <div class="profilesen">Design a sustainable home</div>
          <p>
            施⼯現場を監理するのは技術・経験ともに豊富なオーダーメイド専⾨の建築⼠。
            <br />
            丁寧なヒアリングを軸として皆様のご要望をお伺いし、理想の空間をご提案します。
            <br />
            <br />
            一緒に「これからの住まい」について考えていきましょう。
          </p>
          <div class="buttonde">
            <button>詳しくはこちら</button>
          </div>
        </div>
      </div>
    </main>
    <div class="works">
      <div class="row worksh3">
        <h3 class="col-6">WORKS</h3>
        <div class="col-6 viewall">
          <nuxt-link to="/works">VIEW ALL</nuxt-link>
        </div>
      </div>
      <hooper class="workscontent" :settings="hooperSettings">
        <slide class="workscontenta">
          <nuxt-link to="/works">
            <div class="image-wrap">
              <img src="/images/funazaki.jpg" alt="" />
            </div>
            <h4>船崎邸</h4>
            <p>「経年変化を楽しむ家」</p>
          </nuxt-link>
        </slide>
        <slide class="workscontenta">
          <nuxt-link to="/works">
            <div class="image-wrap">
              <img src="/images/mon.jpg" alt="" />
            </div>
            <h4>モン・プチパレ(M様アトリエ兼美術館)</h4>
            <p>「⻑年の夢を叶えたプチ美術館」</p>
          </nuxt-link>
        </slide>
        <slide class="workscontenta">
          <nuxt-link to="/works">
          <div class="image-wrap">
              <img src="/images/Ksama.jpg" alt="" />
            </div>
            <h4>Ｋ様邸</h4>
            <p>「パートナーや⼤好きなネコとのんびり暮らせる家」</p>
          </nuxt-link>
        </slide>
        <hooper-navigation slot="hooper-addons"></hooper-navigation>
      </hooper>
    </div>
    <AppFooter />
    <Appmodal />
  </div>
</template>

<script>
import { 
  Hooper,
  Slide,
  Navigation as HooperNavigation
   } from 'hooper';
import 'hooper/dist/hooper.css';

export default {
  name: 'App',
  components: {
    Hooper,
    Slide,
    HooperNavigation
  },
  data() {
      return {
        hooperSettings: {
          itemsToShow: 1,
          infiniteScroll: true,
          wheelControl: false,
          autoPlay: true,
          playSpeed: 2000,
          transition: 800,
          breakpoints: { // breakpointを用いたいときはsettingsでまとめないとうまく渡せない
          768: {
            itemsToShow: 2 // 小数点以下の値も指定できる
          },
        }
        },
      }
    }
};
</script>

<style scoped>
.container-fluid {
  max-width: 1600px;
  font-family: sans-serif;
  line-height: 2em;
  letter-spacing: 0.04em;
}
h1 {
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 31px;
  font-weight: 550;
}

.header {
  background-image: url("/images/mainvisual01.jpg");
  background-size: cover;
  background-position: center;
  width: 100vw;
  height: 100vw;
  max-height: 100vh;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.headerh1 {
  width: 100%;
  padding-left: 40px;
  padding-top: 22%;
}
.headerimg {
  padding-left: 40px;
  padding-bottom: 30%;
}
.headerimg img {
  width: 50%;
}

.message {
  padding: 100px 0;
}
.message h2 {
  font-family: arial;
  font-weight: 600;
  padding-bottom: 50px;
}

.messagevertical {
  writing-mode: vertical-rl;
  margin: 0px 30px 50px 0px;
  font-size: 25px;
  font-family: serif;
  z-index: 1;
}
.sustainablelogo {
  text-align: center;
}
.messagepos {
  position: relative;
}
.messageusuimg {
  position: absolute;
  top: 25%;
  right: 0;
}
.messageusuimg img {
  width: 100%;
}
.contentsimage {
  position: relative;
}
.contentsimage h2 {
  position: absolute;
  top: 30px;
  left: 28px;
  color: white;
  font-family: arial;
  font-weight: 700;
}

.contentsimage img {
  width: 100%;
}
.contentsen {
  margin: 40px 0 60px;
}
.contentsen2 {
  margin-bottom: 30px;
}
.contentsen2 h3 {
  font-family: serif;
  line-height: 2em;
}
.forclient {
  margin: 80px 30px;
  display: flex;
  flex-wrap: wrap;
  max-width: 1600px;
  justify-content: center;
}
.forclientitem1 {
  width: 100%;
}
.forclientitem2 {
  width: 100%;
}
.forclientimg {
  width: 100%;
}
.profileimg {
  width: 100%;
}
.forclient2 {
  padding: 40px 40px;
  background-color: #eee;
}
.forclient2 h3 {
  font-size: 40px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 700;
  margin-bottom: 30px;
}
.profileflex {
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  max-width: 1600px;
}
.profileitem {
  width: 100%;
}

.profilelogo {
  position: relative;
}
.profilelogo div {
  position: absolute;
  bottom: -40px;
  right: 10px;
}
.profilebw {
  font-family: arial;
  font-size: 100px;
  font-weight: 400;
  color: #333;
}
.profilebw span {
  color: white;
}
.profileh2 {
  margin: 40px 30px 50px;
}
.profileh2 h2 {
  font-family: serif;
  font-size: 18px;
  font-weight: 800;
  margin-bottom: 0px;
}
.profilesen {
  font-family: arial;
  font-weight: 500;
  font-size: 16px;
  color: #d0d0d0;
  margin-bottom: 30px;
}
.buttonde {
  text-align: center;
}
.buttonde button {
  padding: 10px 60px;
  background-color: black;
  color: white;
}

.works {
  background-color: #f5f5f5;
  padding: 50px 30px 10px;
}
.image-wrap{
  position: relative;
  padding-top: 60%;
    margin: 20px 20px;
}
.image-wrap img {
  position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.worksh3 {
  padding-bottom: 5vw;
}
.worksh3 h3 {
  font-size: 36x;
  font-family: serif;
  font-weight: 400;
}
.viewall {
  text-align: right;
}
.viewall a {
  color: #333;
}
.workscontenta h4 {
  margin: 10px 0px;
  font-family: serif;
  color: #333;
  font-size: 17px;
  padding-left: 3%;
}
.workscontenta p {
  font-family: Arial, Helvetica, sans-serif;
  color: #333;
  font-size: 14px;
  padding-left: 2%;
}
.hooper{
  height: 100%;
}
.hooper-next {
    right: 2%;
    top: -4%;
    background-color: #fff;
    border: 1px solid #f5f3f0;
    padding: 0.6rem;
}
.hooper-prev{
  top: -4%;
  left: 2%;
      background-color: #fff;
    border: 1px solid #f5f3f0;
    padding: 0.6rem;
}
a:hover{
  text-decoration: none;
}

@media screen and (min-width: 768px) {
  .header {
    width: calc(100vw - 117px);
    height: 100vw;
    max-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  h1 {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 3rem;
    font-weight: 600;
    letter-spacing: 5px;
  }
  .headerh1 {
    width: 50%;
    padding-left: 100px;
    padding-top: 0;
  }
  .headerimg {
    width: 50%;
    margin-left: auto;
    padding-right: 20px;
    text-align: right;
    padding-bottom: 0;
  }

  .headerimg img {
    width: 39%;
  }
  .messageleft {
    padding: 0 80px;
  }
  .sustainablelogo {
    margin-top: 100px;
    text-align: left;
  }
  .messageusuimg {
    position: absolute;
    top: 50%;
    right: 30px;
    width: 47%;
  }
  .forclient {
    flex-direction: row-reverse;
    background-color: #888;
  }
  .forclientitem1 {
    width: 55%;
  }
  .forclientitem2 {
    width: 45%;
  }
  .forclient2 {
    align-self: flex-end;
    padding: 140px 80px;
  }
  .forclient2 h3 {
    font-size: 73px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 700;
    margin-bottom: 45px;
  }

  .buttonde {
    padding-top: 40px;
    text-align: left;
  }
  .profileitem {
    width: 47%;
  }
  .profileh2 {
    align-self: center;
    margin: 40px 0px 50px;
    padding: 0px 80px;
  }
  .profilelogo div {
    bottom: 80%;
    right: -218px;
  }
  .profilebw {
    font-size: 104px;
  }
  .profileh2 h2 {
    font-size: 29px;
  }
  .profilesen {
    font-family: arial;
    font-weight: 500;
    font-size: 27px;
    color: #d0d0d0;
    margin-bottom: 30px;
  }
  .works {
    margin: 100px 0px 20px 50px;
  }
}
@media screen and (min-width: 1600px) {
  .forclient {
    margin: 80px auto;
  }
}
</style>
