<template>
  <div class="works">
    <div class="back">
      <div class="header">
        <p>WORKS</p>
        <p>2022 - 2023</p>
      </div>
      <div class="menu">
        <div class="dplanex work">
          <p>CLONE CODING / VANILLA JS</p>
          <p>DPLANEX</p>
          <img src="../assets/dplanex-main.png" />
        </div>
        <div class="travello work">
          <p>UX DESIGN / UI DESIGN / VANILLA JAVASCRIPT</p>
          <p>TRAVELLO</p>
          <img src="../assets/travello-main.png" />
        </div>
        <div class="puppy work">  
          <p>UX DESIGN / UI DESIGN / REACT</p>
          <p>PUPPY</p>
          <img src="../assets/puppy-main.png" />
        </div>
        <div class="bbubbu work">
          <p>UX DESIGN / UI DESIGN / NEXT JS</p>
          <p>BBU BBU</p>
          <img src="../assets/bbubbu-main.png" />
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
      .menu{
        width: calc(100vw - 12.5rem);
        margin: 0 auto;
        display: flex;
        justify-content: space-evenly;
        .work{
          p{
            transform: rotate(-90deg);
          }
          img{
            width: 18.75rem;
          }
        }
      }
    }
  }
</style>