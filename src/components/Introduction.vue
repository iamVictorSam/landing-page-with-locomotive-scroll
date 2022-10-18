<template>
  <section data-scroll data-scroll-speed="2" data-scroll-section>
    <h1 data-scroll-speed="2" data-scroll>
      Welcome to Jexxi Code
      <br />
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nostrum tenetur
      magnam natus repellat quod dolorem culpa excepturi doloremque, autem.
    </h1>

    <div>
      <img src="../assets/man-thinking.png" />
    </div>
  </section>
</template>

<style scoped>
section {
  display: flex;
  align-items: end;
  justify-content: center;
  background-image: url("../assets/background.png");
  height: 100vh;
}

h1 {
  display: flex;
  font-size: 3rem;
  text-align: center;
  color: black;
  padding-left: 3rem;
  margin-bottom: 15rem;
}

img {
  height: 650px;
}
</style>
