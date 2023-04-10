<template>
  <div class="hello">
    <div class="header">
      <div class="main">
        <div class="top">
          <h2>JUEUN</h2>
          <div class="sub">
            <p class="subtext">I AM STUDYING WEB DESIGN AND FRONT-END</p>
            <p class="subtext">💛ANY PROBLEM CAN BE SOLVED POSITIVELY💛</p>
            <p class="scroll">SCROLL TO EXPLORE</p>
          </div>
        </div>
        <div class="bottom">
          <h2>PORTFOLIO</h2>
          <img src="../assets/ju2018.png" />
        </div>
      </div>
    </div>
    <div class="works">
      <div class="work-main">
        <div class="back">
          <h2 class="top">PARTICIPATED</h2>
          <div class="bottom">
            <p>2022<span></span>2023</p>
            <h2>WORKS</h2>
          </div>
        </div>
      </div>
      <div class="dplanex work">
        <div class="top">
          <p class="sublogo">PARTICIPATED</p>
          <p class="num">01<span></span>04</p>
          <p class="sublogo">WORKS</p>
        </div>
        <div class="middle">01</div>
        <div class="bottom">
          <div class="text">
            <p>CLONE CODING / VANILLA JS</p>
            <h2>DPLANEX</h2>
          </div>
          <div class="image">
            <img src="../assets/dplanex-main.png"/>
          </div>
        </div>
        
      </div>
      <div class="travello work">
        <div class="top">
          <p class="sublogo">PARTICIPATED</p>
          <p class="num">02<span></span>04</p>
          <p class="sublogo">WORKS</p>
        </div>
        <div class="middle">02</div>
        <div class="bottom">
          <div class="text">
            <p>UX DESIGN / UI DESIGN / VANILLA JAVASCRIPT</p>
            <h2>TRAVELLO</h2>
          </div>
          <div class="image">
            <img src="../assets/travello-main.png"/>
          </div>
        </div>
        
      </div>
      <div class="puppy work">
        <div class="top">
          <p class="sublogo">PARTICIPATED</p>
          <p class="num">03<span></span>04</p>
          <p class="sublogo">WORKS</p>
        </div>
        <div class="middle">03</div>
        <div class="bottom">
          <div class="text">
            <p>UX DESIGN / UI DESIGN / REACT</p>
            <h2>PUPPY</h2>
          </div>
          <div class="image">
            <img src="../assets/puppy-main.png"/>
          </div>
        </div>
        
      </div>
      <div class="bbu-bbu work">
        <div class="top">
          <p class="sublogo">PARTICIPATED</p>
          <p class="num">04<span></span>04</p>
          <p class="sublogo">WORKS</p>
        </div>
        <div class="middle">04</div>
        <div class="bottom">
          <div class="text">
            <p>UX DESIGN / UI DESIGN / NEXT JS</p>
            <h2>BBU BBU</h2>
          </div>
          <div class="image">
            <img src="../assets/bbubbu-main.png"/>
          </div>
        </div>
        
      </div>
    </div>
    <div class="about">
      <div class="main">
        <div class="top">
          <h2>GOOD TO SEE YOU!</h2>
          <router-link to="/about" @click="closeMenu"><p class="more">LEARN MORE</p></router-link>
        </div>
        <div class="middle">
          <img src="../assets/ju2018.png" />
          <h2>LET ME TELL YOU</h2>
        </div>
        <div class="bottom">
          <h2>ABOUT ME</h2>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="back">
        <div class="menu">
          <div class="siteMap subMenu">
            <p class="num">01/</p>
            <div class="menuContainer">
              <h3>SITEMAP</h3>
              <router-link to="/" @click="closeMenu">HOME</router-link>
              <router-link to="/works" @click="closeMenu">WORKS</router-link>
              <router-link to="/about" @click="closeMenu">ABOUT</router-link>
              <router-link to="/contact" @click="closeMenu">CONTACT</router-link>
            </div>
          </div>
          <div class="socials subMenu">
            <p class="num">02/</p>
            <div class="menuContainer">
              <h3>SOCIALS</h3>
              <router-link to="/" @click="closeMenu">GIT</router-link>
              <router-link to="/works" @click="closeMenu">INSTAGRAM</router-link>
              <router-link to="/about" @click="closeMenu">NOTION</router-link>
            </div>
          </div>
          <div class="contact">
            <router-link to="/contact" @click="closeMenu">LET'S WORK TOGETHER</router-link>
          </div>         
        </div>
        <div class="leejueun">
          <p>PORTFOLIO 2023</p>
          <h2>LEE JU EUN</h2>
          <div class="sidemenu">
            <router-link to="/contact" @click="closeMenu">INFOS & CREDITS</router-link>
            <router-link to="/" @click="closeMenu">BACK TO TOP</router-link>
          </div>
        </div>
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
  .header{
    .main{
      width: calc(100% - 12.5rem);
      height: 100vh;
      color: #252C35;
      padding-top: 6.25rem;
      margin: 0 auto;
      h2{
        font-size: 28.125rem;
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
          font-size: 1.875rem;
          .subtext{
            margin-bottom: 10%;
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
  }
  .works{
    .work-main{
      width: 100vw;
      height: 100vh;
      position: relative;
      .back{
        position: absolute;
        bottom: 0;
        background-color: #252C35;
        width: 100%;
        height: calc(100% - 6.25rem);
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
              font-size: 2.5rem;
              font-weight: 100;
              margin-right: 25rem;
              padding-top: 12.5rem;
              span{
                display: inline-block;
                width: 12.5rem;
                height: 1px;
                background-color: #fff;
                margin: 0 0.9375rem;
              }
            }
          }
        }
      }
    .work{
      width: 100vw;
      height: 100vh;
      padding: 6.25rem;
      color: white;
      position: relative;
      .top{
        display: flex;
        justify-content: space-between;
        .sublogo{
          font-family: 'Bebas Neue', cursive;
          font-size: 3.125rem;
        }
        .num{
          font-family: 'Raleway', sans-serif;
          font-size: 1.5625rem;
          font-weight: 100;
          line-height: 2;
          span{
            display: inline-block;
            width: 12.5rem;
            height: 1px;
            background-color: #fff;
            margin: 0 0.9375rem 0.625rem;
          }
        }
      }
      .middle{
        font-family: 'Bebas Neue', cursive;
        font-size: 25rem;
        opacity: 0.5;
        position: absolute;
        top: 42%;
        right: 5%;
        transform: translateY(-50%);
      }
      .bottom{
        .text{
          position: absolute;
          bottom: 10%;
          p{
            font-family: 'Raleway', sans-serif;
            font-size: 1.875rem;
          }
          h2{
            font-family: 'Bebas Neue', cursive;
            font-size: 18.75rem;
          }
        }
        .image{
          position: absolute;
          bottom: 10%;
          right: 5%;
        }
      }
    }
    .dplanex{
      background-color: #60269E;
    }
    .travello{
      background-color: #26489E;
    }
    .puppy{
      background-color: #F0BC00;
    }
    .bbu-bbu{
      background-color: #E00F35;
    }
  }
  .about{
    width: 100vw;
    height: 100vh;
    .main{
      width: calc(100% - 12.5rem);
      margin: 0 auto;
      padding-top: 6.25rem;
      font-family: 'Bebas Neue', cursive;
      font-size: 15.625rem;
      color: #252C35;
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      .top{
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
        margin-bottom: 3rem;
        h2{
          margin-right: 5rem;
        }
        p{
          font-family: 'Raleway', sans-serif;
          font-size: 1.875rem;
          line-height: 4;
        }
      }
      .middle{
        display: flex;
        margin-bottom: 3rem;
        img{
          margin-right: 4rem;
        }
      }
    }
  }
  .footer{
    width: 100vw;
    height: 100vh;
    border: 1px solid red;
    position: relative;
    .back{
      position: absolute;
      bottom: 0;
      background-color: #252C35;
      width: 100%;
      height: calc(100% - 6.25rem);
      border-top-right-radius: 50px;
      border-top-left-radius: 50px;
      color: #fff;
      font-family: 'Raleway', sans-serif;
      padding-top: 3.125rem;
      .menu{
        display: flex;
        justify-content: space-around;
        margin-bottom: 6rem;
        .subMenu{
          display: flex;
          .num{
            margin-right: 10%;
            font-size: 1.25rem;
          }
          .menuContainer{
            display: flex;
            flex-direction: column;
            font-size: 1.875rem;
            h3{
              font-size: 1.875rem;
              margin-bottom: 22%;
            }
            a{
              font-size: 1.5625rem;
              color: #fff;
              margin-bottom: 18%;
            }
          }
        }
        .contact{
          font-size: 1.875rem;
          a{
            color: #fff;
            text-decoration: underline;
          }
        }
      }
      .leejueun{
        max-width: 82rem;
        margin: 0 auto;
        position: relative;
        p{
          text-align: right;
          transform: translate(-1rem, 2rem);
        }
        h2{
          font-family: 'Bebas Neue', cursive;
          font-size: 25rem;
          text-align: center;
        }
        .sidemenu{
          display: flex;
          justify-content: space-between;
          font-size: 1.5625rem;
          transform: translateY(-2rem);
          a{
            color: #fff;
          }
        }
      }
    }
  }
}
</style>
