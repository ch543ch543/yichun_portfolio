<template>
  <div class='footer'>
  <Contact />
      <p class="footer-class" style="color:lightslategrey">© 2020 - Yichun Tsai</p>
  </div>
</template>

<script>
import Contact from "../components/Contact.vue";

export default {
  name: "footerr",
  components :{
    Contact
  },

  data() {
    return {
      hover1: false,
      hover2: false,
      hover3: false,
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .footer {
    background-color: rgb(40, 48, 48);
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-bottom: 10px;
    padding-top: 10px;
  }
  .container {
    width: 50%;
    margin-top: 30px;
    margin-bottom: 30px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .fab {
    margin-left: 30px;
    margin-right: 30px;
    color: white;
  }
  .active {
    color: burlywood;
    text-decoration: none;
    cursor: pointer;
  }
  
</style>
