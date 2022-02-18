<script>
  

</script>

<template>
  <main>
    <div class="d-flex px-4">
      <div class="box">
        <div class="box-top pb-2 d-flex justify-content-between">
          <h5>Total Customers</h5>
          <i class="grey fa-solid fa-ellipsis-vertical"></i>
        </div>
        <div class="box-btm d-flex justify-content-between">
          <div class="left">
            <h1 class="pb-2">2,420</h1>
            <p class="grey pt-3"><span class="green px-1"><i class="fa-solid fa-arrow-up pe-1"></i>40%</span>vs last month</p>
          </div>
          <div>
            <img src="../assets/images/Green.png" alt="error" class="chart">
          </div>
        </div>
      </div>
      <div class="box">
        <div class="box-top pb-2 d-flex justify-content-between">
          <h5>Members</h5>
          <i class="grey fa-solid fa-ellipsis-vertical"></i>
        </div>
        <div class="box-btm d-flex justify-content-between">
          <div class="left">
            <h1 class="pb-2">1,210</h1>
            <p class="grey pt-3"><span class="red px-1"><i class="fa-solid fa-arrow-down pe-1 arrow-down"></i>10%</span>vs last month</p>
          </div>
          <div>
            <img src="../assets/images/Red.png" alt="error" class="chart">
          </div>
        </div>
      </div>
      <div class="box">
        <div class="box-top pb-2 d-flex justify-content-between">
          <h5>Active now</h5>
          <i class="grey fa-solid fa-ellipsis-vertical"></i>
        </div>
        <div class="box-btm d-flex justify-content-between">
          <div class="left">
            <h1 class="pb-2">316</h1>
            <p class="pt-3"><span class="green px-1"><i class="fa-solid fa-arrow-up pe-1"></i>20%</span>vs last month</p>
          </div>
          <div>
            <img src="../assets/images/Green.png" class="chart">
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
  .box {
    width: 32%;
    padding: 30px 20px;
    margin: 0px 20px;
    border: 2px solid #EAECF0;
    border-radius: 8px;
    color: #101828;
    box-shadow: 0px 1px 3px rgba(16, 24, 40, 0.1), 0px 1px 2px rgba(16, 24, 40, 0.06);
  }

  .grey {
    color: #98A2B3;
  }

  .green {
    color: #027A48;
  }
  
  .red {
    color: #B42318;
  }

  .arrow-down {
    color: #F04438;
  }

  .chart {
    height: 100px;
    width: 200px;
    left: 0px;
    top: 0px;
    border-radius: 0px;
  }

</style>
