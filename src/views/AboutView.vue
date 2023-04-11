<template>
  <div class="about">
    <section class="main">
      <p>hello!</p>
      <p>I am Ju-eun, living in Korea</p>
      <img src="../assets/태극기.png" />
      <p>since 1998.</p>
      <p>I am studying web design and</p>
      <p>front-end since September 2022.</p>
      <p>My goal is to be</p>
      <p>a designer and engineer</p>
      <p>who can contribute to others.</p>
    </section>
    <section class="skill">
      <h2>I USE THESE TOOLS TO WORK</h2>
      <div class="skills">
        <h3>#FRONT-END SKILL</h3>
        <div class="content">
          <div class="detail">
            <img src="../assets/html5.png"/>
            <div class="text">
              <h4>HTML5</h4>
              <p>웹 접근성, 표준성을 준수하며 시멘틱태그를 이용해 마크업 할 수 있습니다.</p>
            </div>
          </div>
          <div class="detail">
            <img src="../assets/css3.png"/>
            <div class="text">
              <h4>CSS3</h4>
              <p>POSITION, DISPLAY를 적절히 사용하여 반응형웹을 적용할 수 있습니다.</p>
            </div>
          </div>
          <div class="detail">
            <img src="../assets/sass.png"/>
            <div class="text">
              <h4>SASS</h4>
              <p>SCSS의 문법과 모듈화를 잘 활용하여  스타일 작업을 원활히 할 수 있습니다.</p>
            </div>
          </div>
          <div class="detail">
            <img src="../assets/js.png"/>
            <div class="text">
              <h4>JAVASCRIPT</h4>
              <p>JAVASCRIPT의 배열, 메소드, FUNCTION을 이해하며 다양한 상활에 적용할 수 있습니다. </p>
            </div>
          </div>
          <div class="detail">
            <img src="../assets/jquery.png"/>
            <div class="text">
              <h4>JQuery</h4>
              <p>관련 라이브러리와 애니메이션, 여러  메소드들을 잘 활용할 수 있습니다.</p>
            </div>
          </div>
          <div class="detail">
            <img src="../assets/reactjs.png"/>
            <div class="text">
              <h4>react.js</h4>
              <p>react 구조와 여러가지 hook들을 잘 알고 있으며, 범용적이고 재사용가능한 컴포넌트 설계를 할 수 있습니다.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped lang="scss">
  .about{
    width: 100%;
    height: 100vh;
    font-family: 'Bebas Neue', cursive;
    .main{
      padding: 150px 100px;
      font-size: 9.0625rem;
      line-height: 1.25;
      img{
        display: inline;
      }
      :nth-child(2){
        display: inline;
      }
    }
    .skill{
      background-color: #252C35;
      padding: 150px 100px;
      color: #fff;
      display: flex;
      width: 100%;
      height: 100vh;
      h2{
        width: 44rem;
        font-size: 12rem;
        margin-right: 4%;
      }
      .skills{
        width: 1000px;
        h3{
          text-align: center;
          width: 273px;
          font-family: 'Raleway', sans-serif;
          font-size: 1.5625rem;
          border: 1px solid white;
          line-height: 2;
          border-radius: 10px;
          margin-bottom: 5%;
        }
        .content{
          display: flex;
          flex-wrap: wrap;
          .detail{
            display: flex;
            border: 1px solid white;
            border-radius: 20px;
            padding: 50px;
            width: 450px;
            margin-right: 3%;
            margin-bottom: 3%;
            img{
              margin-right: 5%;
            }
            .text{
              h4{
                font-size: 30px;
                margin-bottom: 3%;
              }
              p{
                line-height: 1.5;
                font-family: 'Raleway', sans-serif;
              }
            }
          }
        }
      }
    }
  }
</style>