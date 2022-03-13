<template>
  <div id="app">
    <div class="header-container">
            <div class="header">
                <div class="logo">
                    <img src="/images/foyer-coin-des-cieux-website-logo-3.svg"/>
                </div>
            </div>
        </div>
        <nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-dark">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <div class="navbar-nav mr-auto justify-content-center mx-auto">
                <router-link to="/" class="nav-item nav-link">Our Work</router-link>
                <router-link to="/about" class="nav-item nav-link">About Us</router-link>
                <router-link to="/give" class="nav-item nav-link">Ways to Give</router-link>
                <router-link to="/blog" class="nav-item nav-link">Blog</router-link>
               <router-link to="/donate" class="nav-item nav-link">Donate</router-link>
              </div>
            </div>
          </nav>
    <router-view/>
  </div>
</template>

<style>
body {
    font-family: 'Montserrat', Arial, Helvetica, sans-serif;
}
/* Menu */
.bg-dark {
    background-color: #3B848C !important;
  }

  .navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
    color: #F2B56B;
  }
  
  .navbar-dark .navbar-nav .nav-link {
    color: #ffffff;
    font-weight: normal;
  }

  .navbar-nav {
      display: flex;
      justify-content: center;
  }

  .header-container {
    color: #3b3b3b;
    background-color: #3B848C;
    display: flex;
    justify-content: center;
  }
  
  .header {
    display: flex;
    justify-content: center;
  }

  /* .navbar-nav > li{
    padding-left:40px;
    padding-right:40px;
  } */
  #app .nav-link {
  padding-left: 40px;
  padding-right: 40px;
  text-align: center;
  font-weight: normal;
}

  
</style>
