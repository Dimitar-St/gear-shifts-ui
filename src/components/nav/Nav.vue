<script>
 </script>

<template>
<nav class="navbar border-bottom border-2 bg-body-tertiary fixed-top pb-1 mt-1">
  <div class="container-fluid">
    <img class="navbar-brand float-start h-15 w-15 object-fill" href="#" src="@/assets/New GearShifts Logo.png"></img>
    <button class="navbar-toggler bg-white" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon">
      </span>
          Меню
    </button>
    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
      <div class="offcanvas-header">
        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item fs-6">
            <i class="bi bi-person-circle"></i>
            <a class="nav-link" aria-current="page" href="#">Профил</a>
          </li>
          <li class="nav-item fs-6">
            <i class="bi bi-car-front"></i>
            <a class="nav-link" aria-current="page" href="#">График</a>
          </li>
          <li class="nav-item fs-6">
            <i class="bi bi-calendar-date"></i>
            <a class="nav-link" aria-current="page" href="#">Коли</a>
          </li>
          <li class="nav-item fs-6">
            <i class="bi bi-camera"></i>
            <a class="nav-link" aria-current="page" href="#">Запиши</a>
          </li>
          <li class="nav-item fs-6">
            <i class="bi bi-gear"></i>
            <a class="nav-link" aria-current="page" href="#">Услуги</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</nav>
</template>

<style>
</style>
