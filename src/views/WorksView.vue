<template>
  <div class="works">
    <div class="back">
      <header>
        <p>WORKS</p>
        <p>2022 - 2023</p>
      </header>
      <section class="menu">
        <div class="dplanex work">
          <div class="text">
            <p class="detail">CLONE CODING / VANILLA JS</p>
            <p class="title">DPLANEX</p>
          </div>
          <img src="../assets/dplanex-main.png" />
        </div>
        <div class="travello work">
          <div class="text">
            <p class="detail">UX DESIGN / UI DESIGN / VANILLA JAVASCRIPT</p>
            <p class="title">TRAVELLO</p>
          </div>
          <img src="../assets/travello-main.png" />
        </div>
        <div class="puppy work">
          <div class="text">
            <p class="detail">UX DESIGN / UI DESIGN / REACT</p>
            <p class="title">PUPPY</p>
          </div>
          <img src="../assets/puppy-main.png" />
        </div>
        <div class="bbubbu work">
          <div class="text">
            <p class="detail">UX DESIGN / UI DESIGN / NEXT JS</p>
            <p class="title">BBU BBU</p>
          </div>
          <img src="../assets/bbubbu-main.png" />
        </div>
      </section>
      <div class="content">
        <div class="background-d"></div>
        <div class="background-t"></div>
        <div class="background-p"></div>
        <div class="background-b"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  // 마우스 호버하면 active 추가되는 함수 만들기
}
</script>
<style scoped lang="scss">
  .works{
    width: 100vw;
    height: 100vh;
    background-color: #252C35;
    .back{
      width: 100vw;
      height: 100vh;
      padding-top: 8.375rem;
      color: #fff;
      position: relative;
      z-index: 2;
      header{
      display: flex;
      justify-content: space-between;
      width: calc(100vw - 12.5rem);
      margin: 0 auto;
      font-family: 'Raleway', sans-serif;
      font-size: 1.25rem;
      }
      .menu{
        width: 50rem;
        height: 105rem;
        margin: 0 auto;
        display: flex;
        transform: rotate(-90deg) translateX(30rem);
        flex-direction: column;
        align-items: flex-start;
        justify-content: space-around;
        .work{
          display: flex;
          align-items: center;
          height: 300.36px;
          .text{
            .detail{
              font-family: 'Raleway', sans-serif;
              font-size: 1.2rem;
              margin-bottom: 2%;
            }
            .title{
              font-family: 'Bebas Neue', cursive;
              font-size: 9.375rem;
            }
          }
          img{
            width: 300.36px;
            height: 236px;
            transform: rotate(90deg);
            display: none;
          }
        }
        .work .text:hover + img{
          display: block;
        }
      }
      .content{
        position: absolute;
        width: 100%;
        height: 100vh;
        left: 0;
        top: 0;
        z-index: -1;
        div{
          position: absolute;
          width: 100%;
          height: 100%;
          left: 0;
          top: 100%;
        }
        .active{
          top: 0;
        }
        .background-d{
          background-color: #60269E;
          opacity: 0.7;
        }
        .background-t{
          background-color: #26289e;
          opacity: 0.7;
        }
        .background-p{
          background-color: #9e9626;
          opacity: 0.7;
        }
        .background-b{
          background-color: #9e2626;
          opacity: 0.7;
        }
      }
    }
  }
</style>