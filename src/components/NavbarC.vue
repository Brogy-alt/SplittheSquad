<template>
        <div>
        <header>
    <div class="test">
      <nav class="navbar navbar-expand-lg sticky">
      <div class="container-fluid bg-transparent">
        <a class="navbar-brand bg-transparent text-dark"  style="font-family: 'Fjalla One', sans-serif; font-size: 25px;" href="#">SPLITTHESQUAD</a>
        <button class="navbar-toggler text-bg-dark" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse " id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0" style="font-family: 'Fjalla One', sans-serif; font-size: 19px;">
            <li class="nav-item">
              <a class="nav-link active text-dark" aria-current="page" href="/" style="margin-right: 10rem;">HOME</a>
            </li>      
          </ul>
        </div>
      </div>
    </nav>
    </div>
  
</header>
    </div>
</template>

<script>
export default {
  name: 'NavbarC'
}
</script>

<style scoped>
.navbar, .container-fluid {
    background-color: transparent;
    /* position: relative; */
    backdrop-filter: blur(5px);
    
  }  
  
  .navbar-toggler , .navbar-toggler-icon {
    color: #000000;
  };

  .navbar-toggler {
    border-color: rgb(0, 0, 0);
  };
</style>