<template>
  <hooper>
  <slide>
    slide 1
  </slide>
  <slide>
    slide 2
  </slide>
  <slide>
    slide 3
  </slide>
  <slide>
    slide 4
  </slide>
  <slide>
    slide 5
  </slide>
  <slide>
    slide 6
  </slide>

</hooper>
</template>

<script>
import { Hooper, Slide } from 'hooper';
import 'hooper/dist/hooper.css';

export default {
  name: 'App',
  components: {
    Hooper,
    Slide
  }
};
</script>

<style scoped>
.hooper-slide {
    background-color: #62caaa;
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    border: 2px solid #fff;
    font-size: 30px;
    border-radius: 10px;
  }
</style>