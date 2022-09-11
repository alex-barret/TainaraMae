<template>
  <header>
    <div class="container">
      <nav class="navbar navbar-expand">
        <a href="#" class="link navbar-brand mr-auto">Tainara Mãe de Santo</a>
        <div class="links mr-2">
          <a href="#" class="btn mr-5">Home </a>
          <a href="#" class="btn mr-5">Trabalho </a>
          <a href="#" class="btn mr-5"> Sobre</a>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  background-color: #981bd2;
}
#logo {
  width: 150 px;
  height: 100%;
}

.links {
  display: inline-flex;
}
.links a {
  color: #fff;
  font-weight: bolder;
}

.links a:focus {
  outline: none !important;
  box-shadow: none !important;
}
.link {
  color: #fff;
  font-size: 30px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bolder;
}
</style>