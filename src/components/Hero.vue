<template>
  <div class="hero">
    <div class="hero-text">
      <h2>Jumbotron</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore, nobis!
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
.hero {
  display: flex;
  height: 80vh;
  width: 100%;
  position: relative;
  background-image: url(../assets/night-bg.jpg);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.hero::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
  height: 100%;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}
.hero-text {
  margin: auto;
  position: relative;
  z-index: 2;
}
.hero-text h2 {
  font-size: 5rem;
  color: #fff;
}
.hero-text p {
    font-size: 1.3rem;
    color: #fff;
    font-style: italic;
}
</style>