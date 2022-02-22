<script>

  export default {
    name: 'pageHeader',

  }
</script>

<template>
  <header class="welcome d-flex flex-sm-column flex-lg-row px-5 py-5 justify-content-between">
    <div class="left">
      <h2>Welcome back, Olivia</h2>
      <p class="header-text">Track, manage and forecast your customers and orders.</p>
    </div>
    <div class="right">
      <button class="btn mx-3 mx-sm-0"><img src="../assets/images/upload.png" class="px-2">Import</button>
      <button class="btn btn-1 px-3 text-center mx-lg-1"><img src="../assets/images/plus.png" class="px-2" >Add</button>
    </div>
  </header>
</template>

<style scoped>
 .btn-1 {
  background: #7F56D9;
  color: #fff;
 }

 .header-text {
   color: #667085;
 }
</style>