<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="main">
    <div class="navbar">
      <img
        src="https://cdn3d.iconscout.com/3d/premium/thumb/game-controller-4035922-3342601.png"
        class="logo"
      />
      <ul>
        <li>
          <a href=""><RouterLink to="/">HOME</RouterLink></a>
        </li>
        <li>
          <a href=""><RouterLink to="/about">ABOUT</RouterLink></a>
        </li>
        <li>
          <a href="#"><RouterLink to="/skill">EXPERIENCE</RouterLink></a>
        </li>
        <li>
          <a href="#"><RouterLink to="/work">MY PROJECTS</RouterLink></a>
        </li>
        <li>
          <a href="#"><RouterLink to="/contact">CONTACT</RouterLink></a>
        </li>
      </ul>
    </div>
    <div class="info">
      <h3>Hi, Welcome To My Profile.</h3>
      <h1>
        <span>GA</span>ME <span><br />DE</span>VELOPER
      </h1>
      <div class="icon-list">
        <a href="https://github.com/AnudhaUthsala"
          ><img src="https://cdn-icons-png.flaticon.com/512/25/25231.png"
        /></a>
        <a href=""
          ><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png"
        /></a>
        <a href="">
          <img
            src="https://www.iconpacks.net/icons/2/free-twitter-logo-icon-2429-thumb.png"
        /></a>
      </div>
      <a class="button-style" href="#">Contact Me</a>
    </div>

    <div class="image">
      <img
        src="https://cdn-icons-png.flaticon.com/512/1792/1792287.png"
        class="Game"
        style="height: 500px"
      />
    </div>
    <div class="icons">
      <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
      <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
      <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
    </div>
  </div>
</template>

<style scoped>
.navbar {
  width: 86%;
  display: flex;
  margin: auto;
  padding: 15px 0;
  align-items: center;
  justify-content: space-between;
}

.icon-list {
  display: flex;
  justify-content: space-between;
  padding: 10px;
  margin-top: 10px;
  cursor: pointer;
  width: 150px;
}

.icon-list > a > img {
  width: 30px;
  text-decoration: none;
}

.navbar .logo {
  width: 100px;
  cursor: pointer;

  margin-left: -2%;
}

ul {
  margin-top: -4%;
}

ul li {
  list-style: none;
  display: inline-block;
  padding: 10px 16px;
}

ul li a {
  font-size: 16px;
  font-weight: bold;
  text-decoration: underline overline;
  color: rgb(79, 51, 202);
  margin-top: -3%;
  transition: 0.4s ease;
}

ul li a:hover {
  color: rgb(0, 0, 0);
}

.info {
  margin-left: 7%;
  align-items: center;
  margin-top: 15%;
}

.info h1 {
  font-size: 85px;
  color: rgb(190, 80, 24);
}

.info h3 {
  font-size: 25px;
  letter-spacing: 1px;
  line-height: 24px;
}

.info span {
  color: rgb(110, 17, 110);
}

.button-style {
  text-decoration: none;
  color: #030303;
  background: rgb(189, 91, 235);
  margin: 26px 0;
  padding: 10px 18px;
  border-radius: 10px;
  display: inline-block;
  transition: 0.4s ease;
}

.button-style:hover {
  background: rgb(59, 174, 209);
}

.image {
  width: 30%;
  height: 60%;
  position: absolute;
  right: 100px;
  bottom: 0;
}

.image img {
  position: absolute;
  height: 140%;
  left: 40%;
  transform: translate(-55%);
  bottom: 0;
  transition: left 2s ease;
}

.icons a {
  text-decoration: none;
  color: #000;
}

.icons ion-icon {
  margin-left: 7%;
  color: #000;
  margin-right: -60px;
  font-size: 40px;
  transition: 0.4s ease;
}

.icons ion-icon:hover {
  color: rgb(59, 174, 209);
}
</style>
