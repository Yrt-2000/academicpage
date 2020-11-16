<template>
  <div id="app">
    <div class="bar">
      Zhimeng Yin
    </div>
    <div class="other">
      <div class="basic">
        <div class="info">
          <div class="head">Zhimeng Yin</div>
          <p>abababababababa</p>
          <p>abababababababa</p>
          <p>abababababababa</p>
          <p>abababababababa</p>
        </div>
        <div class="photo">
          <img src="./assets/unnamed.jpg"/>
        </div>    
      </div>
      <div class="interests">
        <div class="head2">Research Interests</div>
        <ul class="a">
          <li>Coffee</li>
          <li>Tea</li>
          <li>Coca Cola</li>
        </ul>
      </div>
      <div class="cv">
        <div class="head2">CV</div>
        <div class="cvInfo">
          <div class="left">
            <ul class="a">
              <li>Coffee</li>
              <li>Tea</li>
              <li>Coca Cola</li>
            </ul>
          </div>
          <div class="right">
            <ul class="b">
              <li>Coffee</li>
              <li>Tea</li>
              <li>Coca Cola</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  // components: {
  //   HelloWorld
  // }
}
</script>

<style>
/* #app{
  padding: 0;
  margin:0 ;
} */
/* body{
  background-size: 100%;
} */
.bar{
  position: fixed;
  top: 0px;
  left: 0px;
  background-color: black;
  color: aliceblue;
  text-align: left;
  font-size: 25px;
  font-family:'Times New Roman', Times, serif;
  padding: 20px 20px;
}
.other{
  display:flex;
  width:1150px;
  padding-top: 105px;
  flex-direction: column;
  margin:0 auto;
  background-color: antiquewhite;
}
.basic{
  display: flex;
  flex-direction: row;
}
.info{
  width: 70%;
}
.photo{
  background-color: aquamarine;
  width: 30%;
}
img{
  width: 50%;
  margin-left: 30%;
  margin-top: 5%;
}
.head{
  color:rgb(8, 53, 177);
  font-size:25px ;
  padding-bottom: 18px;
}
.head2{
  color:rgb(8, 53, 177);
  font-size:25px ;
  padding-bottom: 4px;
}
.interests{
  margin-top: 45px;
}
ul.a{
  list-style-type:square;
  margin-top: 0px;
  padding-left: 18px;
  font-size: 14px;
  line-height: 25px;
}
ul.b{
  list-style-type:none;
  margin-top: 0px;
  padding-left: 18px;
  font-size: 14px;
  line-height: 25px;
}
.cv{
  margin-top: 45px;
}
.cvInfo{
  display: flex;
  flex-direction: row;
}
.left{
  width: 70%;
  background-color: aquamarine;
}
</style>
