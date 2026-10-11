<template>

    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/contact">contact</router-link> -->
<nav>
  <nav class="navbar navbar-expand-lg bg-warning-subtle">
    <div class="container">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/contact">contact</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/Grade">Grade</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              API
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="/golds">ราคาทอง</a></li>
              <li><a class="dropdown-item" href="/product_api">สินค้า</a></li>
              <li><a class="dropdown-item" href="users">ผู้ใช้</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</nav>

  <router-view/>
</template>


