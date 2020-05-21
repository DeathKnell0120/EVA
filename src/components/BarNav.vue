<template>
  <div id="BarNavega">
    <nav class="navbar navbar-expand-lg py-3 navbar-dark bg-dark shadow-sm">
  <div class="container">
    <a href="#" class="navbar-brand">
      <!-- Logo Image -->
      <img src="/gow.png" width="45" alt="" class="d-inline-block align-middle mr-2">
      <!-- Logo Text -->
      <span class="text-uppercase font-weight-bold">EVA</span>
    </a>
    <button type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler"><span class="navbar-toggler-icon"></span></button>
    <div id="navbarSupportedContent" class="collapse navbar-collapse">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active"><a href="/index.html" class="nav-link">Inicio <span class="sr-only">(current)</span></a></li>
        <li class="nav-item"><a href="#quines" class="nav-link">Quienes somos</a></li>
        <li class="nav-item"><a href="#serviciosEmpresa" class="nav-link">Nuestros Servicios</a></li>
        <li class="nav-item"><a href="#misRedes" class="nav-link">Contactos</a></li>
      </ul>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {
  name: "BarNav"
};
</script>