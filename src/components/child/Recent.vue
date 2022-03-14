<template>
  <div class="m-recent">
    <div class="m-recent-header">
      <div class="m-recent-header-title">
        <h1>Recent Infographics</h1>
      </div>
    </div>
    <div class="m-recent-content">
      <div class="m-recent-content-slide">
        <div class="m-slide-item">
          <img src="../../assets/content/img/fist-recent.jpg" alt="" />
          <div class="m-item-icon"></div>
          <div class="m-item-logo"></div>
          <div class="m-item-text"></div>
        </div>
        <div class="m-slide-item">
          <img src="../../assets/content/img/ethenum.png" alt="" />
          <div class="m-item-icon"></div>
          <div class="m-item-logo"></div>
          <div class="m-item-text"></div>
        </div>
        <div class="m-slide-item">
          <img src="../../assets/content/img/report.png" alt="" />
          <div class="m-item-icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16.6155 10.4618L21.5385 10.4618M21.5385 10.4618L21.5385 15.3848M21.5385 10.4618L10.4617 21.5385"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M15.3848 21.5378L10.4618 21.5378M10.4618 21.5378L10.4618 16.6149M10.4618 21.5378L21.5385 10.4611"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <rect
                x="0.75"
                y="0.75"
                width="30.5"
                height="30.5"
                rx="15.25"
                stroke="#E6E8EC"
                stroke-width="1.5"
              />
            </svg>
          </div>
          <div class="m-item-logo"></div>
          <div class="m-item-text">
            <h1>Attack Wagon Performance After Listing</h1>
          </div>
        </div>
        <div class="m-slide-item">
          <img src="../../assets/content/img/pig.jpg" alt="" />
          <div class="m-item-icon"></div>
          <div class="m-item-logo"></div>
          <div class="m-item-text"></div>
        </div>
        <div class="m-slide-item">
          <img src="../../assets/content/img/last-recent.jpg" alt="" />
          <div class="m-item-icon"></div>
          <div class="m-item-logo"></div>
          <div class="m-item-text"></div>
        </div>
      </div>
    </div>
    <div class="m-recent-footer">
      <div class="m-slide-dot">
        <svg
          width="22"
          height="14"
          viewBox="0 0 22 14"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M7.86358 0.397811C7.25486 -0.164098 6.30587 -0.126144 5.74396 0.482583L0.8978 5.73252C0.367404 6.30711 0.367399 7.19277 0.897788 7.76737L5.74395 13.0174C6.30585 13.6262 7.25484 13.6641 7.86357 13.1022C8.47231 12.5403 8.51027 11.5913 7.94837 10.9826L5.42595 8.24995L20 8.24995C20.8284 8.24995 21.5 7.57838 21.5 6.74995C21.5 5.92152 20.8284 5.24995 20 5.24995L5.42601 5.24995L7.94836 2.51744C8.51027 1.90871 8.47231 0.95972 7.86358 0.397811Z"
            fill="#777E91"
          />
        </svg>

        <div class="m-dot"></div>
        <div class="m-dot"></div>
        <div class="m-dot"></div>
        <div class="m-dot"></div>
        <div class="m-dot"></div>
        <svg
          width="22"
          height="14"
          viewBox="0 0 22 14"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M14.1364 0.397811C14.7451 -0.164098 15.6941 -0.126144 16.256 0.482583L21.1022 5.73252C21.6326 6.30711 21.6326 7.19277 21.1022 7.76737L16.256 13.0174C15.6941 13.6262 14.7452 13.6641 14.1364 13.1022C13.5277 12.5403 13.4897 11.5913 14.0516 10.9826L16.574 8.24995L2 8.24995C1.17157 8.24995 0.499999 7.57838 0.499999 6.74995C0.499999 5.92152 1.17157 5.24995 2 5.24995L16.574 5.24995L14.0516 2.51744C13.4897 1.90871 13.5277 0.95972 14.1364 0.397811Z"
            fill="#777E91"
          />
        </svg>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.m-recent {
  .m-recent-header {
    margin-top: 78px;
    .m-recent-header-title {
      display: flex;
      align-items: center;
      justify-content: center;
      h1 {
        font-weight: 700;
        font-size: 32px;
        color: #23262f;
      }
    }
  }
  .m-recent-content {
    .m-recent-content-slide {
      //   grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
      //   display: grid;
      //   grid-gap: 24px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 50px;
      .m-slide-item {
        margin-left: 30px;
        position: relative;
        img {
          width: 404px;
          height: 263px;
          border-radius: 16px;
        }
        &:nth-child(3) {
          img {
            width: 492px;
            height: 321px;
            border-radius: 16px;
          }
        }
        .m-item-icon {
          position: absolute;
          top: 15px;
          right: 15px;
        }
        .m-item-logo {
          position: absolute;
          bottom: 16px;
          left: 16px;
          background-image: url(../../assets/content/img/logo.png);
          width: 109px;
          height: 41px;
          background-repeat: no-repeat;
        }
        // &:nth-child(3){
        //      position: absolute;
        //   bottom: 16px;
        //   left: 16px;
        //   background-image: url(../../assets/content/img/logo.png);
        //   width: 109px;
        //   height: 41px;
        //   background-repeat: no-repeat;
        // }
        .m-item-text {
          position: absolute;
          bottom: 15px;
          right: 61px;

          h1 {
            font-weight: 500;
            font-size: 16px;
            color: #ffffff;
          }
        }
      }
    }
  }
  .m-recent-footer {
      margin-top: 44px;
      margin-bottom:64px;
    .m-slide-dot {
      display: flex;
      justify-content: center;
      padding-top: 24px;
      align-items: center;
      .m-dot {
          cursor: pointer;
        width: 12px;
        height: 12px;
        border-radius: 50%;
        background-color: #b1b5c3;
        margin-right: 10px;
        &:nth-child(3) {
          background-color: #1777ee;
          width: 16px;
          height: 16px;
        }
      }
      svg{
          margin:0 24px 0 14px;
          cursor: pointer;
      }
    }
  }
}
</style>