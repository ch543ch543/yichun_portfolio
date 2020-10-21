<template>
  <div class="about">
    <a name='about'>
        <div class="title">
          <h1>ABOUT ME</h1>
        </div>
        <div data-aos="fade-up" data-aos-duration="2000">
          <div class="content" >
            <img class="yichun" src="../assets/yichun3.jpg">
            <div>
              <p style="font-size: medium; text-align: left;">你好，我叫蔡宜君，政大統計碩士畢業後第一份工作
                期間有稍微使用到網頁html及css，發現這是所有工作內容中最令我感興趣的，於是利用下班後的時間自己在網路上接觸網頁工程相關資訊，並毅然決然地決定全力往這個方向前進。<br>
                我相信不論是什麼工作剛開始一定都會有非常多需要學習的地方，以一個前端工程領域超級新鮮人的我來說更是，但我對於一切的挑戰與學習充滿期待。<br>
                若對我有興趣的話歡迎參考我的作品集，並希望能有機會更近一步的會談與認識。<br><br>
                I'm excited to start my new journey with new challenges and gains as a web developer.
                If you feel interested, welcome to give my portfolio a look, and looking forward to talk to you soon!
              </p>
            <Contact></Contact>
          </div>
          </div>
          <hr>
        </div>
    </a>
  </div>
</template>

<script>
import Contact from "../components/Contact.vue";

export default {
  name: "About",
  components: {
    Contact
  }
};
</script>

<style>
.about {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color:rgb(40, 48, 48);
  color: white;
}
.container {
  width: 100%;
  margin-top: 50px;
  margin-bottom: 50px;
  padding-left: 0px;
  padding-right: 0px;
}
.content {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-bottom: 70px;
  padding-left: 30px;
  padding-right: 30px;
}
.content p {
        width: 600px
      }
.title{
  margin-bottom: 30px;
  margin-top: 70px;
}
.yichun {
  margin-right: 50px;
  margin-left: 50px;
}
a {
  width: 100%;
}
p {
width: 60%
}
img {
  width: 20%;
  border: 10px solid #9dc5c2;
}
h1 {
  font-size: 200%;
}



@media (max-width: 600px) {
  .about {
  width: 100%;
  min-height: 70vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color:rgb(40, 48, 48);
  }
  h1 {
  font-size: 100%;
  margin-top: 10px;
  }
  img {
  width: 200px;
  }
  .container {
    margin-top: 50px;
    margin-bottom: 50px;
    padding-left: 0px;
    padding-right: 0px;
  }
  .content {
    margin-bottom: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  } 
  .content p {
        max-width: 300px
      }
  .yichun {
    margin-bottom: 10px;
  }
  .title{
    margin-bottom: 30px;
    margin-top: 30px;
  }
  p {
    width: 60%
  }

}

</style>