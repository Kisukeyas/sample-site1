<template>
  <div>
    <a href="#" class="btn" @click="modalOpen">モーダル起動</a>
    <div>
      <p v-for="n in 30" :key="n">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusamus
        blanditiis cum ducimus eos exercitationem, facilis harum nobis provident
        quod, sint tempore tenetur voluptas. Consectetur nobis officia optio
        quod tempora.
      </p>
    </div>
    <div v-if="modal">
      <div class="p-modal__overlay" @click="modalClose" />
      <div class="p-modal__container">
        <div class="p-modal__content">
          <h2 class="p-modal__header">text</h2>
          <div class="p-modal__body">
            <p v-for="n in 2" :key="n">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. A
              accusamus blanditiis cum ducimus eos exercitationem, facilis harum
              nobis provident quod, sint tempore tenetur voluptas. Consectetur
              nobis officia optio quod tempora.
            </p>
          </div>
          <div class="p-modal__footer">
            <a href="#" class="p-modal__btn" @click="modalClose"
              >モーダル閉じる</a
            >
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
  },
};
</script>
<style>
.p-modal__overlay {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.7);
  min-height: 100vh;
}
.p-modal__container {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 100;
}
.p-modal__content {
  min-width: 350px;
  max-width: 500px;
  margin: 0 auto;
  background-color: #fff;
  padding: 16px 24px;
  box-sizing: border-box;
  border-radius: 5px;
}
.p-modal__btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 8px 24px;
  background-color: #333;
  color: #fff;
  text-decoration: none;
  border-radius: 30px;
  cursor: pointer;
}
.p-modal__footer {
  text-align: center;
}
</style>