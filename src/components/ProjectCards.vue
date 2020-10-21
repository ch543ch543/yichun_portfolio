<template>
    <div class="projectcards">
      <div class="container">
          <div class="cards d-flex flex-column">
                <h2 >PERSONAL PROJECTS</h2>
                <div class="topofcard" style="margin-bottom:150px">
                  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" style="margin-bottom:70px"> 
                    <ol class="carousel-indicators">
                      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                      <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
                      <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
                      <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
                    </ol>
                    <div class="carousel-inner">
                      <div class="carousel-item active" >
                        <img class="d-block " src="../assets/Vueshop/vue1.png" alt="First slide">
                      </div>
                      <div class="carousel-item">
                        <img class="d-block" src="../assets/Vueshop/vue2.png" alt="Second slide">
                      </div>
                      <div class="carousel-item">
                        <img class="d-block" src="../assets/Vueshop/vue3.png" alt="Third slide">
                      </div>
                      <div class="carousel-item">
                        <img class="d-block" src="../assets/Vueshop/vue4.png" alt="Third slide">
                      </div>
                      <div class="carousel-item">
                        <img class="d-block" src="../assets/Vueshop/vue5.png" alt="Third slide">
                      </div>
                      <div class="carousel-item">
                        <img class="d-block" src="../assets/Vueshop/vue6.png" alt="Third slide">
                      </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="sr-only">Next</span>
                    </a>
                  </div>
                

                <div class="personalcard text-left " >
                  <h1>Vue shop</h1>
                  <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Excepturi neque, ipsa animi maiores repellendu distinctioaperiam earum dolor voluptatum consequatur blanditiis inventore debitis fuga numquam voluptate architecto itaque molestiae.</p>
                  <button class="btn btn-info btn-lg"> Link </button>
              </div>

              </div>
              <h2 style="text-align: left; color: rgb(38, 42, 43); border-bottom: rgb(99, 161, 163) solid;">PRACTICE PROJECTS</h2>
              <div class="card" style="margin-top:50px">
                <div class="rightofcard">
                  <img class="practice" src="../assets/smartbrain.png" > 
                </div>
                <div class="leftofcard text-left">
                  <h1>Smart Brain</h1>
                  <p>
                    使用Clarifai偵測人臉API<br>
                    記錄使用者的操作次數<br>
                    Ｔilt.js及particle.js視覺美化<br>
                    使用Heroku建立使用者資料庫以及部署網頁<br>
                  </p>
                  <a href="https://smart-brainnnn.herokuapp.com/" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
              <div class="card">
                <div class="rightofcard">
                  <img class="practice" src="../assets/weather.png">
                </div>
                <div class="leftofcard text-left">
                  <h1>Easy Ｗeather App </h1>
                    <p>使用axios套件封裝async及await串接Weatherbit.io天氣API，讓使用者能自由搜尋各城市當下及未來五天的氣溫。</p>
                  <a href="https://ch543ch543.github.io/weatherapp/" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
              <div class="card">
                <div class="rightofcard">
                  <img class="practice" src="../assets/RobotFriends.png" > 
                </div>
                <div class="leftofcard text-left">
                  <h1>Robot Friends</h1>
                    <p>使用state及props紀錄使用者的搜尋文字並過濾出相對應的機器人</p> 
                  <a href="https://ch543ch543.github.io/reactRobot/" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
              <div class="card">
                <div class="rightofcard">
                  <img class="practice" src="../assets/nasa.png"> 
                </div>
                <div class="leftofcard text-left">
                  <h1>NASA Image API Practice</h1>
                  
                    <p>串連NASA的每日天文圖片資料庫</p>
                 
                  <a href="https://ch543ch543.github.io/api_nasaphoto/" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
              <div class="card">
                <div class="rightofcard">
                  <img class="practice" src="../assets/fries.png"> 
                </div>
                <div class="leftofcard text-left">
                  <h1>Restaurant Website (html& css)</h1>
                  <p>使用html及css建立薯條餐廳官網的畫面</p>
                  <a href="https://ch543ch543.github.io/fries.github/index.html" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
              <div class="card">
                <div class="rightofcard">
                  <img class="practice" src="../assets/todolist.png"> 
                </div>
                <div class="leftofcard text-left">
                  <h1>TodoList</h1>
                  <p> 使用者能自行新增、刪除以及將代辦事項標記完成。</p>
                  <a href="https://ch543ch543.github.io/todolist/" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
              <div class="card">
                <div class="rightofcard">
                  <img class="practice" src="../assets/landingpage.png"> 
                </div>
                <div class="leftofcard text-left">
                  <h1>Landing Page</h1>
                  <p>MailCamp註冊及訂閱模板連結</p>
                  <a href="https://ch543ch543.github.io/landingpage.zerotomaster/" target="_blank" class="btn btn-info btn-lg"> Link </a>
              </div>
              </div>
          </div>
      </div>
    </div>
  </template>
  
  <script>
  // import ProjectPics from './ProjectPics';

  export default {
    name: "projectcards",
    // components:{
    //   ProjectPics
    // },
    data(){
      return{
        pic: "../assets/logo.png",
      }
    },
  };
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
    .projectcards {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .container {
      margin-top: 50px;
      margin-bottom: 50px;
      font-size: 50px;
    }
    .card {
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: center;
      background-color: transparent;
      border-color: transparent;
      margin-top: 100px;
      margin-bottom: 100px;
    }
    .leftofcard {
      width: 40%;
      margin-left: 40px;
    }
    .leftofcard a {
      width: 75px;
    }
    img.d-block {
      width: 700px;
      margin-left: auto; 
      margin-right: auto;
    }
    img.practice {
        width: 500px;
      }

    .leftofcard h1, .personalcard h1{
      font-size: 0.8em;
    }

    .leftofcard p, .personalcard p{
      font-size: 0.3em;
      }
    
    .cards h2{
      font-size: 2rem;
      width: 100%;
      text-align: left;
      color: rgb(38, 42, 43);
      border-bottom: solid rgb(99, 161, 163);
      margin-bottom: 50px;
      box-shadow: cadetblue;
    } 
    p {
      width: 100%;
    }
    li {
      padding: 5px;
    }
    
    @media (max-width: 600px){
      .projectcards {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
      }
      .container {
        margin-top: 30px;
        margin-bottom: 30px;
        font-size: 20px;
      }
      .card {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        background-color: transparent;
        border-color: transparent;
        margin-top: 150px;
        margin-bottom: 150px;
      }
      .leftofcard {
        width: 100%;
        margin-top: 5px;
        margin-left: 0px;
      }
      p { 
        width: 100%;
      }
      img.d-block {
        width: 300px;
        margin-left: auto; 
        margin-right: auto;
        }
      img.practice {
        width: 90%;
      }
      .leftofcard h1, .personalcard h1{
        font-size: 0.8em;
      }
      .leftofcard p, .personalcard p{
        font-size: 0.3em;
      }
      .cards h2{
        font-size:  2rem;
      }

    }  

    @media (min-width: 600px) and (max-width: 992px){
      .projectcards {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
      }
      .container {
        margin-top: 50px;
        margin-bottom: 50px;
        font-size: 30px;
      }
      .card {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        background-color: transparent;
        border-color: transparent;
        margin-top: 50px;
        margin-bottom: 50px;
      }
      .leftofcard {
        width: 100%;
        margin-top: 5px;
        margin-left: 0px;
      }
      .rightofcard {
        width: 100%;
      }
      p { 
        width: 100%;
      }
      img.d-block {
        width: 600px;
        }
      img.practice {
        width: 90%;
      }
      .leftofcard h1, .personalcard h1{
      font-size: 120%;
      }

      .leftofcard p, .personalcard p{
      font-size: 50%;
      }

      .cards h2{
      font-size: 0.8em;
      }
    }  

      /* @media (min-width: 992px) {
        .container {
         max-width: 1200px;
         min-width: 992px;
        }
        img.d-block {
          min-width: 992px;
        }
        img.practice {
          width: 600px;
        }
      }   */
  </style>
  