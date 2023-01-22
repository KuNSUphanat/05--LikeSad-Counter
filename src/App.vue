<script setup>
import PhotoCard from "./components/PhotoCard.vue";
</script>

<template>
  <header>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container d-flex justify-content-between">
        <a class="navbar-brand d-flex align-items-center" href="#"
          ><i class="fab fa-instagram social-icon"></i><strong>&nbsp;Instagram</strong></a
        >
      </div>
    </div>
  </header>
  <main role="main">
    <section class="jumbotron text-center">
      <div class="container">
        <div style="display:flex ;">
          <div class="card-header">
            <img src="/src/Profile.jpg" alt="Profile Image" class="profile-img">
          </div>
          <div class="card-header">
            <img src="/src/Profile.jpg" alt="Profile Image" class="profile-img">
          </div>
          <div class="card-header">
            <img src="/src/Profile.jpg" alt="Profile Image" class="profile-img">
          </div>
          <div class="card-header">
            <img src="/src/Profile.jpg" alt="Profile Image" class="profile-img">
          </div>
          <div class="card-header">
            <img src="/src/Profile.jpg" alt="Profile Image" class="profile-img">
          </div>
          <div class="card-header">
            <img src="/src/Profile.jpg" alt="Profile Image" class="profile-img">
          </div>
        </div>

      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="row">
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
        </div>
      </div>
    </div>
  </main>
  <footer class="text-muted">
    <div class="container">
      <p class="float-right"><a href="#">Back To Top</a></p>
    </div>
  </footer>
</template>

<style scoped>
.card-header {
    position: relative;
    height: 48px;
    margin: 0px 7%;
}
.card-header .profile-img {
    width: 130px;
    height: 130px;
    border-radius: 1000px;
    position: absolute;
    left: 0%;
    transform: translate(-50%, -50%);
    border: 8px solid #000000;
    box-shadow: 0 0 20px #00000033;
}
.card-header .profile-img:hover {
    width: 180px;
    height: 180px;
    border: 8px solid #ffffff79;
}
</style>
