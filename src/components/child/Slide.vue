<template>
  <div class="m-slide">
    <div class="m-slide-bcg">
      <div class="m-slide-left">
        <div class="m-slide-left-text">
          <p>A CRYPTO PLATFORM</p>
          <h1>
            Tracking privite and <br />
            public fundraising.
          </h1>
          <p>
            Include latest information on seed,private,strategic,and IDO/IEO
            rounds
          </p>
        </div>
      </div>
      <div class="m-slide-right">
        <div class="m-slide-right-avatar">
          <img src="../../assets/content/img/man-coin.png" alt="" />
        </div>
      </div>
    </div>
    <div class="m-slide-dot">
      <div class="m-dot"></div>
      <div class="m-dot"></div>
      <div class="m-dot"></div>
      <div class="m-dot"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.m-slide {
  .m-slide-bcg {
    display: flex;
    width: 1230px;
    height: 455px;
    margin-top: 40px;
    border-radius: 15%;
    height: 455px;
    // justify-content:space-between;
    -webkit-clip-path: polygon(
      0% 7%,
      50% 0%,
      100% 7%,
      100% 93%,
      50% 100%,
      0% 93%
    );
    background: linear-gradient(153.06deg, #274060 -0.31%, #1b2845 99.69%);
    .m-slide-left {
      display: flex;
      align-items: center;
      text-align: start;

      .m-slide-left-text {
        padding-left: 73px;
        p {
          &:first-child {
            color: #588dca;
            font-size: 12px;
            font-weight: bold;
          }
          &:last-child {
            color: #b1b5c3;
            font-weight: normal;
          }
        }
        h1 {
          color: #fff;
          font-size: 56px;
          font-weight: 700;
        }
      }
    }
    .m-slide-right {
      .m-slide-right-avatar {
        padding-left: 77px;
      }
    }
  }
  .m-slide-dot {
    display: flex;
    justify-content: center;
    padding-top: 24px;
    align-items: center;
    .m-dot {
      width: 12px;
      height: 12px;
      border-radius: 50%;
      background-color: #b1b5c3;
      margin-right: 10px;
      &:nth-child(2) {
        background-color: #1777ee;
        width: 16px;
        height: 16px;
      }
    }
  }
}
</style>