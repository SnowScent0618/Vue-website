<template>
  <div class="profile">
        <div class="profile-body">
            <div class="profile-picture">
                <img src="img/photos/logo500x500.png">
            </div>

            <div class="name">
                <p>Mert Şişmanoğlu</p>
            </div>

            <div class="text">
                <p>Student and Software Developer</p>
            </div>

            <div class="links">
                <a target="_blank" href="https://github.com/mertssmnoglu"><i class="fab fa-github"></i></a>
                <a target="_blank" href="https://linkedin.com/in/mertssmnoglu"><i class="fab fa-linkedin"></i></a>
                <a target="_blank" href="https://instagram.com/mertssmnoglu"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'ProfileCard'
}
</script>

<style scoped>
.profile {
  text-align: center;
  border-radius: 8px;
  overflow: hidden;
  margin: 0px auto;
  display: block;
  width: 40%;
}

.profile-body {
  background: #2c3a47;
  padding: 60px 40px;
  margin: 0;
}

.profile-picture {
  display: inline-block;
  padding: 8px;
  margin: auto;
}

.profile-picture img {
  display: block;
  width: 100px;
  height: 100px;
  border-radius: 50px;
  outline: 2px solid #000;
  outline-offset: 4px;
}

.name {
  color: white;
  font-size: 28px;
  font-weight: 600;
  margin: 10px 0;
}

.text {
  font-size: 18px;
  font-weight: 500;
  color: #e66767;
}

.links {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0;
  gap: 6px;
}

.links a {
  color: white;
  text-decoration: none;
  font-size: 25px;
  transition: 0.37s;
}

.links a:hover {
  color: #8c52cd;
  transform: scale(1.4);
}

i {
  padding: 10px 10px;
}

@media screen and (max-width: 600px) {
  .profile {
    width: 100%;
    transform: scale(0.9);
  }
}

</style>
