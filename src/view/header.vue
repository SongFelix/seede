<template>
  <div class="seede-header">
    <div class="web-header">
      <div class="left">
        <div class="in-block main-title mr28">
          <img class="" src="@/assets/xide.png" alt="" />
        </div>

        <div class="in-block">
          <div class="font20">设计咨询工作室</div>
          <div class="font20">Seeed Design&Art studio, Beijing</div>
        </div>
      </div>
      <div class="right">
        <div class="in-block mr20">
          <div class="font18">好的设计，就是好的商业</div>
          <div class="font22">Good design is good business</div>
        </div>
        <div class="in-block">
          <img class="flower" src="@/assets/flower.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.web-header {
  padding: 0 80px;
  display: flex;
  justify-content: space-between;
  height: 100%;
  align-items: center;
  .main-title {
    width: 144px;
  }
  .font20 {
    font-family: "Source Han Sans CN";
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    text-align: left;
    height: 30px;
    line-height: 30px;
    color: #232323;
  }
  .font18 {
    font-family: "PingFang SC";
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 25px;
    height: 25px;
    color: #232323;
  }
  .font22 {
    font-family: "Slackside One";
    font-style: normal;
    font-weight: 400;
    font-size: 22px;
    height: 32px;
    line-height: 32px;
    color: #232323;
  }
  .right {
    text-align: right;
    height: 63px;
    line-height: 63px;
  }
  .flower {
    width: 48px;
    height: 63px;
  }
}
.mr28 {
  margin-right: 28px;
}
.mr20 {
  margin-right: 20px;
}
</style>
