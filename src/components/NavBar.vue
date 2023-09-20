<template>
  <nav
    id="navbar-main"
    class="navbar navbar-expand-lg navbar-dark bg-primary rounded"
  >
    <div class="container">
      <a class="navbar-brand mr-lg-5" href="./index.html">
        <img src="/img/mxli_sys_logo.png" style="width: 50px; height: 50px" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbar_global"
        aria-controls="navbar_global"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-collapse collapse" id="navbar_global">
        <div class="navbar-collapse-header">
          <div class="row">
            <div class="col-6 collapse-close">
              <button
                type="button"
                class="navbar-toggler"
                data-toggle="collapse"
                data-target="#navbar_global"
                aria-controls="navbar_global"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span></span>
                <span></span>
              </button>
            </div>
          </div>
        </div>
        <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
          <li class="nav-item dropdown">
            <a href="#" class="nav-link" data-toggle="dropdown" role="button">
              <i class="ni ni-ui-04 d-lg-none"></i>
              <span class="nav-link-inner--text">What We Do</span>
            </a>
          </li>
          <li class="nav-item dropdown">
            <a href="#" class="nav-link" data-toggle="dropdown" role="button">
              <span class="nav-link-inner--text">About Us</span>
            </a>
          </li>
          <li class="nav-item dropdown">
            <a href="#" class="nav-link" data-toggle="dropdown" role="button">
              <span class="nav-link-inner--text">Contact</span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style>
.navbar {
  width: 100vw;
}
</style>
<script></script>
