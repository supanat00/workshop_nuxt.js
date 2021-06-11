<template>
  <body>
    <div class="container">
      <div class="logo">
        <a href="#">Register</a>
      </div>
      <div class="nav">
        <ul class="items">
          <li><a href="#">Home</a></li>
          <li><a href="#">Product</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
    </div>

    <div class="heading">
      <p>coffee / bekery / shop / cafe</p>
      <h2>Join<span>With</span>Drink</h2>
      <h6>Join Us</h6>
    </div>
    <div class="icon">
      <img src="~assets/icon.png" />
    </div>
    <footer>
      <div class="footer-bottom">
        <p>copyright &copy;2021 capslockz. designed by <span>superman</span></p>
      </div>
    </footer>
  </body>
</template>

<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;1,100&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  overflow: hidden;
  font-family: 'Poppins', sans-serif;
}
body {
  background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url(~assets/Coffee.jpg);
  background-position: center;
  background-size: cover;
  width: 100%;
  height: 100vh;
}

.container {
  padding: 60px 60px 0px 60px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.container .logo {
  background: #fff;
  padding: 10px 22px;
  border-radius: 15px;
}

.container .logo a {
  text-decoration: none;
  color: #333;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  width: 100%;
}

.container .nav .items {
  display: flex;
}

.container .nav .items li {
  padding-right: 20px;
}

.container .nav .items li a {
  text-decoration: none;
  color: #b8b8b8;
  font-size: 16px;
  opacity: 1;
}

.container .nav .items li a:hover {
  color: #fff;
}

.heading {
  position: absolute;
  top: 55%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  flex-direction: column;
  text-align: center;
  align-items: center;
  width: 100%;
}

.heading p {
  color: #b8b8b8;
  letter-spacing: 2px;
}

.heading h2 {
  color: #ffffff;
  font-size: 4em;
  word-spacing: 7px;
  letter-spacing: 10px;
  text-transform: uppercase;
}

.heading h2 span {
  color: #fff;
  font-weight: 100;
}

.heading h6 {
  color: #333;
  font-weight: 700;
  font-size: 12px;
  letter-spacing: 1px;
  text-transform: uppercase;
  background: #fff;
  width: 12%;
  padding: 7px 20px;
  cursor: pointer;
  border-radius: 10px;
}

.icon {
  float: right;
  margin-right: 60px;
  width: 3%;
  position: relative;
  margin-top: -45px;
  opacity: 0;
}

.icon img {
  width: 100%;
}

footer {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(17, 17, 17, 0.562);
  height: auto;
  width: 100vw;
  color: white;
}

.footer-bottom {
  background: rgba(0, 0, 0, 0.438);
  width: 100vw;
  padding: 15px 0;
  text-align: center;
}
.footer-bottom p {
  font-size: 14px;
  word-spacing: 2px;
  text-transform: capitalize;
}
.footer-bottom span {
  text-transform: uppercase;
  opacity: 0.4;
  font-weight: 200;
}

@media only screen and (max-width: 767px) {
  .container {
    padding: 30px 30px 0px 30px;
  }

  .container .logo {
    padding: 6px 13px;
  }

  .container .logo a {
    font-size: 13px;
    letter-spacing: 1px;
  }

  .heading p {
    letter-spacing: 1px;
    font-size: 12px;
    padding-bottom: 5px;
  }

  .heading h2 {
    font-size: 2em;
    word-spacing: 5px;
    letter-spacing: 5px;
  }

  .heading h6 {
    font-size: 10px;
    letter-spacing: 0px;
    width: 25%;
  }

  .container .nav .items li a {
    opacity: 0;
  }

  .icon {
    margin-right: 30px;
    width: 4%;
    margin-top: -30px;
    opacity: 1;
  }

  .footer-bottom {
    padding: 9px 0;
  }
  .footer-bottom p {
    font-size: 10px;
  }
}
</style>
