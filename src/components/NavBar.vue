<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-gradient" id="nav">
    <div class="container">
        <div class="collapse navbar-collapse">
          <ul class="nav justify-content-end" >
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="/about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="/resume">Résumé</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="/projects">Projects</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" aria-current="page" href="/testimonials">Testimonials</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="/contact">Contact</a>
              </li>
          </ul>
        </div>
    </div>
</nav>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style scoped>
#nav {
    background-color: #63458A;
    padding: 20px;
    width: 100%;
}

#nav a {
  font-weight: bold;
  color: #E4B7E5;
}
.nav-item {
  float: right !important;
}
 
</style>  
  <!-- <nav>
    <ul class="nav justify-content-end" id="nav">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="/about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="/resume">Résumé</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="/projects">Projects</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" aria-current="page" href="/testimonials">Testimonials</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="/contact">Contact</a>
          </li>
      </ul>
    </nav> -->