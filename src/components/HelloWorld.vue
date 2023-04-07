<template>
  <div class="hello">
    <div class="content01">
      <div class="top">
        <h2>JUEUN</h2>
        <div class="sub">
          <p class="subtext">I AM STUDYING WEB DESIGN AND FRONT-END</p>
          <p class="scroll">SCROLL TO EXPLORE</p>
        </div>
      </div>
      <div class="bottom">
        <h2>PORTFOLIO</h2>
        <img src="../assets/ju2018.png" />
      </div>
    </div>
    <div class="content02">
      <div class="back">
        <h2 class="top">PARTICIPATED</h2>
        <div class="bottom">
          <p>2022<span></span>2023</p>
          <h2>WORKS</h2>
        </div>
      </div>
    </div>
    <div class="content03">
      <div class="top">
        <p>WORKS</p>
        <p>01<span></span>04</p>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
.hello{
  width: 100vw;
  .content01{
    width: calc(100% - 200px);
    height: 100vh;
    margin: 100px auto 0;
    color: #252C35;
    h2{
      font-size: 500px;
      font-family: 'Bebas Neue', cursive;
    }
    .top{
      display: flex;
      position: relative;
      .sub{
        position: absolute;
        bottom: 20%;
        right: 0;
        font-family: 'Raleway', sans-serif;
        font-size: 30px;
        .subtext{
          margin-bottom: 5%;
        }
        .scroll{
          text-decoration: underline;
        }
      }
    }
    .bottom{
      position: relative;
      img{
        position: absolute;
        bottom: 20%;
        left: 40%;
      }
    }
  }
  .content02{
    width: 100vw;
    height: 100vh;
    position: relative;
    .back{
      position: absolute;
      bottom: 0;
      background-color: #252C35;
      width: 100%;
      height: calc(100% - 100px);
      border-top-right-radius: 50px;
      border-top-left-radius: 50px;
      color: white;
        h2{
          font-family: 'Bebas Neue', cursive;
          font-size: 300px;
        }
        .top{
          position: absolute;
          top: 20%;
          left: 10%;
        }
        .bottom{
          position: absolute;
          bottom: 15%;
          right: 15%;
          display: flex;
          p{
            font-family: 'Raleway', sans-serif;
            font-size: 40px;
            font-weight: 100;
            margin-right: 300px;
            span{
              display: inline-block;
              width: 200px;
              height: 1px;
              background-color: #fff;
              margin: 0 10px;
            }
          }
        }
      }
    }
    .content03{

    }
  }
</style>
