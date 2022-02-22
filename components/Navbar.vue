<script>
  import Button from "./Button.vue"
  import Search from "./Search.vue"

  export default {
    name: "Navbar",

    components: {
      Button,
      Search
    }
  }
</script>

<template>
<div>
  <div class="d-flex px-5 navbar navbar-expand-lg bg-light">
    <a class="navbar-brand" href="#">
      <li class="nav-item d-flex logo">
        <img src="../assets/images/Logomark.png"/>
        <a class="nav-link px-0" href="#">Untitled UI</a>
      </li>
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <img src="../assets/images/burger.png" />
    </button>
    <div class="navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto">
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Home</a> 
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Dashboard</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Project</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Tasks</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Reporting</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Users</a>
        </li>
      </ul>
      <ul class="navbar-nav">
        <Button />
        <li class="icon">
          <a href="#"><img class="px-2" src="../assets/images/settings-icon.png"/>
          </a>
        </li>
        <li class="icon">
          <a href="#"><img class="px-2" src="../assets/images/Bell.png"/>
          </a>
        </li>
        <li>
          <a href="#"><img class="px-2" src="../assets/images/Avatar.png"/>
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="divider"></div>
  <div class="container-fluid px-5 py-2 navbar-collapse d-none d-lg-block" id="navbarSupportedContent">
      <div class="nav-two d-flex justify-content-between">
        <ul class="nav me-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Overview</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Notification</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Analytics</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Saved reports</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Trade History</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">User reports</a>
          </li>
        </ul>
      <Search />
      </div>
    </div>
</div>  

</template>



<style scoped>

nav {
  background: #FFFFFF !important;
}
.logo {
  padding-right: 10px;
  color: #101828 !important;
  width: 150px;
}

.nav-link {
  color: #344054;
  font-weight: 500;
  line-height: 24px;
}

.icon {
  padding: 5px 10px;
}


.active {
  background: #F9FAFB;
  border-radius: 6px;
}

</style>