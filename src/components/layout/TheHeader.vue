<template>
  <div class="m-header">
    <div class="m-header-content">
      <div class="m-header-left">
        <div class="m-header-left-logo">
          <img src="../../assets/content/img/logo.png" alt="" />
        </div>
        <div class="m-header-left-menu">
          <ul class="m-menu">
            <li>Home</li>
            <li>Projects</li>
            <li>Funds</li>
            <li>Events</li>
            <li>Blog</li>
          </ul>
        </div>
      </div>
      <div class="m-header-right">
        <div class="m-header-right-input">
          <input type="text" class="m-input" placeholder="Search" />
          <div class="m-icon-search">
            <img src="../../assets/content/icon/search.jpg" alt="" />
          </div>
        </div>
        <div class="m-header-right-logo">
          <img
            class="m-icon"
            src="../../assets/content/icon/telegram.jpg"
            alt=""
          />
          <img
            class="m-icon"
            src="../../assets/content/icon/twiter.jpg"
            alt=""
          />
          <img
            class="m-icon"
            src="../../assets/content/icon/youtobe.jpg"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.m-header {
  .m-header-content {
    display: flex;
    max-width: 1250px;
    width: 100%;
    .m-header-left {
      display: flex;
      align-items: center;
      .m-header-left-logo {
      }
      .m-header-left-menu {
        .m-menu {
          display: flex;
          align-items: center;
          list-style: none;
          li {
            font-size: 16px;
            font-weight: 600;
            &:first-child {
              color: #1777ee;
              text-decoration: underline;
              text-underline-offset: 4px;
              text-decoration-thickness: 3px;
            }
            &:last-child {
              margin-right: 238px;
            }
            margin-right: 48px;
            color: #666d8f;
          }
        }
      }
    }
    .m-header-right {
      display: flex;
      align-items: center;

      .m-header-right-input {
        display: flex;
        position: relative;
        .m-input {
          align-items: center;
          padding: 0 40px;
          width: 220px;
          height: 40px;
          border: 2px solid #e6e8ec;
          box-sizing: border-box;
          border-radius: 8px;
          margin-right: 40px;
          // margin-left: 190px;
          outline: none;
          &:focus {
          }
        }
        .m-icon-search {
          position: absolute;
          top: 12px;
          left: 12px;
        }
      }
      .m-header-right-logo {
        display: flex;
        .m-icon {
          width: 40px;
          height: 40px;
          margin-right: 16px;
        }
      }
    }
  }
}
</style>