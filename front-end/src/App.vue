<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light">
    <a class="navbar-brand" href="/">
      <img src="/images/download.png" class="logo" alt="Camera Icon" width='80px' height="80px">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-item nav-link" href="/">Home <span class="sr-only"></span></a>
        <a class="nav-item nav-link" href="/resume">Resume</a>
        <a class="nav-item nav-link" href="/Projects">Projects</a>
      </div>
    </div>
  </nav>
    <router-view />
    <div class="footerfix"></div>
  <div class="footer text-center fixed-bottom">
    <div class="container">
      <section class="row">
        <div class="col">
          <a class="footButton" href="https://github.com/chance-robinson/cp3">Github Repo</a>
        </div>
        <div class="col">
          <a class="footButton" href="https://www.linkedin.com/in/chance-robinson/">LinkedIn</a>
        </div>
      </section>
      <div class="text-center p-3">
        <p id="Contact">2022 Copyright: Chance Robinson</p>
      </div>
    </div>
    </div>
  </div>
</template>

<style>
html,
body {
  margin: 0;
  padding: 0;
}

html {
  height: 100%;
}

body {
  position: relative;
  min-height: 100%;
}

#Contact {
  padding-top: 1%;
  text-align: center;
  color: white;
}

.navbar {
  background-color: rgb(125, 241, 241);
  padding-left: 2%;
}

.footerfix {
  height: 9rem;
}

.footer {
  position: absolute;
  right: 0;
  bottom: 0;
  left: 0;
  padding-top: 1%;
  text-align: center;
  background-color: rgb(125, 241, 241);
}

.footButton {
  color: rgb(0, 0, 0);
  padding: 10px 20px;
  display: inline-block;
}

.footButton:hover {
  background-color: rgba(40, 120, 190, 0.37);
  color: white !important;
}

#Contact {
  color: white;
}

.navbar-nav {
  width: inherit;
  font-size: 1.5em;
  margin-left: 2%;
}

.navbar-nav .nav-link:hover {
  background-color: rgba(40, 120, 190, 0.37);
  color: white !important;
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0);
}

.img {
  max-width: 50%;
}

#headertext {
  text-align: center;
  padding-top: 2rem;
  padding-bottom: 1rem;
}

.col-8 {
  text-align: center;
  margin-top: 8px;
  margin-bottom: 8px;
  border-right: 2px dashed #f69c55;
}

.desc .col-4 {
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px dashed #f69c55;
  margin-top: 8px;
  margin-bottom: 8px;
  color: black;
}

</style>