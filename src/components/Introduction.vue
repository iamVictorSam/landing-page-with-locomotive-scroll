<template>
  <main>
    <section class="intro-section">
      <div class="intro-title">
        <h1 data-scroll data-scroll-speed="9">
          Isaac Junior
          <br />A Frontend Engineer and Technical writer with a deep focus on
          creating pixel-perfect designs.
        </h1>
      </div>
      <div class="intro-image">
        <img src="../assets/man-thinking.png" alt="profile" />
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "Introduction",
};
</script>

<style>
.intro-section {
  display: flex;
  align-items: center;
  justify-content: center;
  background-image: url("../assets/background.png");
  height: 100vh;
}

.intro-title {
  display: flex;
  font-size: 1rem;
  text-align: center;
  color: white;
}
.intro-image {
  display: flex;
  position: absolute;
  bottom: 0px;
  right: 0px;
}
img {
  height: 600px;
  /* width: 700; */
}
</style>
