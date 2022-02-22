<script>
import Search from './Search.vue';

export default {
  name: 'tableFilter',

  components: { 
    Search 
  }
}
</script>

<template>
  <div class="d-flex flex-sm-column-reverse flex-lg-row px-5 mt-3 my-5 justify-content-between">
    <div class="filter d-flex flex-sm-column-reverse flex-lg-row mt-2 text-center">
      <div class="d-flex">
        <div class="colored fw-bold mx-2 p-2">
          All time
          <i class="fa-solid fa-xmark"></i>
        </div>
        <div class="colored fw-bold mx-2 p-2">
          US,AU,+4
          <i class="fa-solid fa-xmark"></i>
        </div>
      </div>
      <div class="plain btn fw-bold mx-2 p-2">
        <img src="../assets/images/filter.png" alt="filter">
        More filters
      </div>
    </div>
    <Search />
  </div>
</template>

<style>
  .plain {
    color: #344054;
  }
  .colored {
    background: #F9F5FF;
    color: #6941C6;
    border-radius: 8px;
  }
</style>

