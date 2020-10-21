<template>
  <div class="yichun">
    <div class="container">
      <p>Hi, my name is 蔡宜君 <br> This is my portfolio</p>
      <div class="button">
        <router-link to="/CV" class="btn btn-info btn-lg font-weight-bold">CV</router-link>
        <a href="#about" class="btn btn-info btn-lg font-weight-bold" >About me</a>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "yichun",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.yichun { 
  background: url(https://images.unsplash.com/photo-1492551557933-34265f7af79e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80) no-repeat center center fixed;
  background-size: cover;
  overflow: hidden;
  width: 100%;
  height: 100vh;
  margin: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
p {
  width: 60%;
  font-size: 3rem;
  font-weight: 900;
  color: white;
  background-color: rgba(40, 48, 48, 0.932);
  border-width: 0px;
  padding-left: 15px;
  padding-right: 15px;
}
a {
  width:150px;
  margin-left:10px;
}
.btn-info {
    color: #fff;
    background-color: #17504c;
    border-color:  #17504c;
}
@media (max-width: 992px){
  .container {
  text-align: center;
  }
  p {
  text-align: center;
  font-size: 2rem;
  font-weight: 900;
  width: 60%;
  margin-bottom: 10px;
}
  a {
    text-align: center;
    font-size: 100%;
  }
  .btn {
   margin-bottom: 10px;
  }
}

</style>
