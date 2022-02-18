<template>
  <form>
    <div class="d-flex search px-2">
      <img class="d-block search-icon" src="../assets/icons/search.png">
      <input class="input py-2 h-100" type="text" placeholder="Search" aria-label="Search">
    </div>
  </form>
</template>

<script>

export default {
  name: 'Search',
}
</script>

<style>
  .search {
  background: #FFFFFF;
  border: 2px solid #D0D5DD;
  box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);
  border-radius: 8px;
  width: 350px;
  padding-left: 10px;
  }

  .search-icon {
  height: 20px;
  width: 20px;
  top: 8px;
  border: none;
  }

  .input {
  background: #FFFFFF;
  border: none;
  width: 100%;
  margin-left: 5px;
  }
</style>