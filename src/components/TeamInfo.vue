<template>
  <div>
      <h2 style="text-align:center">Our Team</h2>
          <div class="row">
            <div class="about-column">
              <div class="card">
                <img src="/images/people/image13.JPEG" alt="Fritz" style="width:100%">
                <div class="container">
                  <h2>Fritz-Carl Morlant</h2>
                  <p class="title">Director of Social Innovation </p>
                  <p>lorem ipsum ipsum lorem lorem ipsum ipsum lorem lorem ipsum ipsum lorem lorem ipsum ipsum lorem.</p>
                  <p>communications@morlant.org</p>
                  <p><button class="button">Contact</button></p>
                </div>
              </div>
            </div>
          
            <div class="about-column">
              <div class="card">
                <img src="/images/people/image13.JPEG" alt="Fritz" style="width:100%">
                <div class="container">
                  <h2>Fritz-Carl Morlant</h2>
                  <p class="title">Excutive Director</p>
                  <p>lorem ipsum ipsum lorem lorem ipsum ipsum lorem lorem ipsum ipsum lorem lorem ipsum ipsum lorem.</p>
                  <p>director@foyercoindescieux.org</p>
                  <p><button class="button">Contact</button></p>
                </div>
              </div>
            </div>
          
            <div class="about-column">
              <div class="card">
                <img src="/images/people/image13.JPEG" alt="John" style="width:100%">
                <div class="container">
                  <h2>Fritz-Carl Morlant</h2>
                  <p class="title">Developer</p>
                  <p>lorem ipsum ipsum lorem lorem ipsum ipsum lorem lorem ipsum ipsum lorem lorem ipsum ipsum lorem.</p>
                  <p>communications@morlant.org</p>
                  <p><button class="button">Contact</button></p>
                </div>
              </div>
            </div>
          </div>
  </div>
</template>

<script>
export default {
  name: 'TeamInfo',
  props: {
    msg: String,
    msg2: String,
    msg3: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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

  .navbar-nav > li{
    padding-left:40px;
    padding-right:40px;
  }

  .page {
    display: flex;
    flex-wrap: wrap;
  }
  
  .section {
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .content {
    background-color: #EAEDF0;
    height: 600px;
  }

  .photo-grid-container {
    display: flex;
    justify-content: center;
  }
  
  .photo-grid {
    width: 900px;
    display: flex;
    justify-content: flex-start;
  }
  
  .photo-grid-item {
    border: 1px solid #fff;
    width: 300px;
    height: 300px;
  }

  /* Image Grid */
.portfolio {
    display: grid;
    grid-template: auto auto auto auto auto / 1fr 1fr 1fr;
    grid-column-gap: 10px;
    grid-row-gap: 10px;
  }
  
  .image img {
    width: 100%;
  }

#welcome {
  margin: 0 auto;
  border-bottom: 5px solid #3b3b33;
  width: 100%;
  padding: 10px;
  font-family: cursive, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  text-align: center;
}

#intro {
    text-align: center;
    font-family: cursive, sans-serif;
    margin: auto;
    padding: 50;
}

.avatar {
    float: left;
    width: 60px;
    height: 60px;
    margin: 25px;
    border-radius: 40px;
    background-color: #383836;
  }
  
  .username {
    margin-top: 30px;
  }
  
  .comment {
    margin: 10px;
    overflow: hidden;  /* This is important */
  }

  .intro-pic {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 25%;
  }

  .nav-link {
      color: #e4b858;
  }

  img {
    width: 100%;
    height: auto;
}


.row {
    display: flex;
    flex-wrap: wrap;
    padding: 0 4px;
  }
  

  .column {
    flex: 25%;
    max-width: 25%;
    padding: 0 4px;
  }
  
  .column img {
    margin-top: 8px;
    vertical-align: middle;
    width: 100%;
  }
  
  @media screen and (max-width: 800px) {
    .column {
      flex: 50%;
      max-width: 50%;
    }
  }
  
  @media screen and (max-width: 600px) {
    .column {
      flex: 100%;
      max-width: 100%;
    }
  }

.footer {
    color: #EAEDF0;
    position: sticky;
    right: 0;
    bottom: 0;
    left: 0;
    padding: 1rem;
    background-color: #3B848C;
    text-align: center;
  }

  .about-column {
    float: left;
    width: 33.3%;
    margin-bottom: 16px;
    padding: 0 8px;
  }
  
  .card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    margin: 8px;
  }
  
  .about-section {
    padding: 50px;
    text-align: center;
    background-color: #F2B56B;
    color: black;
  }

  .container {
    padding: 0 16px;
  }
  
  .container::after, .row::after {
    content: "";
    clear: both;
    display: table;
  }
  
  .title {
    color: grey;
  }
  
  .button {
    border: none;
    outline: 0;
    display: inline-block;
    padding: 8px;
    color: white;
    background-color: #000;
    text-align: center;
    cursor: pointer;
    width: 100%;
  }
  
  .button:hover {
    background-color: #555;
  }
  
  @media screen and (max-width: 650px) {
    .about-column {
      width: 100%;
      display: block;
    }
  }

  .github {
      color: #F2B56B;
  }
  
</style>
