<template>
  <div class="works">
    <div class="back">
      <div class="header">
        <p>WORKS</p>
        <p>2022 - 2023</p>
      </div>
      <div class="image">
        <img src="../assets/dplanex-main.png" />
        <img src="../assets/travello-main.png" />
        <img src="../assets/puppy-main.png" />
        <img src="../assets/bbubbu-main.png" />
      </div>
      <div class="menu">
        <div class="dplanex work">
          <p class="detail">CLONE CODING / VANILLA JS</p>
          <p class="title">DPLANEX</p>
        </div>
        <div class="travello work">
          <p class="detail">UX DESIGN / UI DESIGN / VANILLA JAVASCRIPT</p>
          <p class="title">TRAVELLO</p>
        </div>
        <div class="puppy work">  
          <p class="detail">UX DESIGN / UI DESIGN / REACT</p>
          <p class="title">PUPPY</p>
        </div>
        <div class="bbubbu work">
          <p class="detail">UX DESIGN / UI DESIGN / NEXT JS</p>
          <p class="title">BBU BBU</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped lang="scss">
  .works{
    width: 100vw;
    height: 100vh;
    .back{
      width: 100vw;
      height: 100vh;
      background-color: #252C35;
      padding-top: 8.375rem;
      color: #fff;
      .header{
      display: flex;
      justify-content: space-between;
      width: calc(100vw - 12.5rem);
      margin: 0 auto;
      font-family: 'Raleway', sans-serif;
      font-size: 1.25rem;
      }
      .image{
        display: flex;
        justify-content: space-evenly;
        img{
            width: 18.75rem;
          }
      }
      .menu{
        width: 42.5rem;
        margin: 0 auto;
        display: flex;
        transform: rotate(-90deg);
        flex-direction: column;
        align-items: flex-start;
        .work{
          p{
            // transform: rotate(-90deg);
          }
          .detail{
            font-family: 'Raleway', sans-serif;
            font-size: 1.875rem;
            margin-bottom: 2%;
          }
          .title{
            font-family: 'Bebas Neue', cursive;
            font-size: 9.375rem;
            margin-bottom: 20%;
          }
        }
      }
    }
  }
</style>