<template>
  <div>
    <button class="modal_box" @click="modalOpenClose">
      <i class="fas fa-bars"></i>
    </button>
    <div v-if="modal">
      <div class="modal_bg" @click="modalClose"></div>
      <div class="modal_flex">
        <div class="modal_nav">
          <h1>SUSTAINABLE ARCHITECT LABORATORY</h1>
          <div class="modal_a">
            <a href="/" class="modal_aa">
              <dl>
                <dt>TOP</dt>
                <dd>トップ</dd>
              </dl>
            </a>
            <a href="/works" class="modal_aa">
              <dl>
                <dt>WORKS</dt>
                <dd>作品一覧</dd>
              </dl>
            </a>
            <a href="" class="modal_aa">
              <dl>
                <dt>PROFILE</dt>
                <dd>プロフィール</dd>
              </dl>
            </a>
            <a href="" class="modal_aa">
              <dl>
                <dt>FOR CLIENT</dt>
                <dd>業務内容やフローなど</dd>
              </dl>
            </a>
            <a href="" class="modal_aa">
              <dl>
                <dt>FLOW</dt>
                <dd>ご依頼の流れ</dd>
              </dl>
            </a>
            <a href="" class="modal_aa">
              <dl>
                <dt>PRIVACY POLICY</dt>
                <dd>プライバシーポリシー</dd>
              </dl>
            </a>
            <a href="" class="modal_aa">
              <dl>
                <dt>CONTACT</dt>
                <dd>お問い合わせ</dd>
              </dl>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      modal: false,
    };
  },
  methods: {
    modalOpen() {
      this.modal = true;
    },
    modalClose() {
      this.modal = false;
    },

    modalOpenClose(){
      console.log("modalOpen",this.modal)
      this.modal = !this.modal;
    },
  },
};
</script>

<style scoped>
a:hover{
  text-decoration: none;
}
.modal_box {
  display: flex;
  align-items: center;
  justify-content: center;
  position: fixed;
  top: 0;
  right: 0;
  height: 100px;
  width: 100px;
  background: #fff;
  z-index: 101;
  border: none;
  padding: 0;
}
.modal_box_2 {
  display: flex;
  align-items: center;
  justify-content: center;
  position: fixed;
  top: 0;
  right: 0;
  height: 100px;
  width: 100px;
  background: #fff;
  z-index: 102;
  border: none;
  padding: 0;
}
i{
  font-size: 65px;
  }
.modal_bg {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  min-height: 100vh;
}
.modal_flex {
  display: flex;
  position: fixed;
  top: 0;
  right: 0;
  z-index: 100;
  height: 100vh;
  width: 50%;
  background-color: #333;
}
.modal_nav {
  align-self: center;
  margin: 0 auto;
  width: 80%;
}
.modal_nav h1 {
  color: #fff;
  font-size: 28px;
  font-family: source-han-serif-japanese, serif;
  margin-bottom: 30px;
}
dd {
  font-size: 14px;
  vertical-align: center;
  margin-left: auto;
  margin-bottom: 0;
}
dt {
  font-size: 26px;
  padding-left: 10px;
}
dl {
  display: flex;
  text-align: right;
  color: #fff;
  font-family: source-han-serif-japanese, serif;
  border-bottom: 1px solid white;
  padding: 5px 0px;
  align-items: center;
}

@media screen and (max-width: 768px) {
  .modal_bg {
    display: none;
  }
  .modal_flex {
    display: flex;
    position: fixed;
    top: 0;
    right: 0;
    z-index: 100;
    height: 100vh;
    width: 100%;
    background-color: #333;
  }
  .modal_nav {
    align-self: center;
    margin: 0 auto;
    width: 80%;
  }
  .modal_nav h1 {
    color: #fff;
    font-size: 25px;
    font-family: source-han-serif-japanese, serif;
    margin-bottom: 40px;
  }
  dd {
    font-size: 13px;
    vertical-align: center;
    margin-left: auto;
    margin-bottom: 0;
  }
  dt {
    font-size: 21px;
    padding-left: 10px;
  }
  dl {
    display: flex;
    text-align: right;
    color: #fff;
    font-family: source-han-serif-japanese, serif;
    border-bottom: 1px solid white;
    padding: 10px 0px;
    align-items: center;
  }
}
</style>