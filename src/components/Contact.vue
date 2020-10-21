<template>
  <div class="contact">
    <div class="container">
      
        <a href="https://github.com/ch543ch543" target="_blank" class="fab fa-github" style="font-size:40px;"
            @mouseover="hover1 = true"
            @mouseleave="hover1 = false"
            :class="{'active': hover1}"></a>
        <a href="https://www.linkedin.com/in/yichun-tsai-859278177" target="_blank" class="fab fa-linkedin" style="font-size:40px;"
            @mouseover="hover2 = true"
            @mouseleave="hover2 = false"
            :class="{'active': hover2}"></a>
        <a href="https://medium.com/@ch543ch543" target="_blank" class="fab fa-medium" style="font-size:40px;"
            @mouseover="hover3 = true"
            @mouseleave="hover3 = false"
            :class="{'active': hover3}"></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "contact",
  props: {
    msg: String
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
  .contact {
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
