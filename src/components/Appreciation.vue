<template>
  <section data-scroll-section>
    <h1
      className="appreciation-text"
      data-scroll
      data-scroll-repeat="true"
      data-scroll-class="animate"
      data-scroll-speed="5"
    >
      Thank You For Using The Locomotive Scroll Library
    </h1>
    <br />
    <h2 data-scroll data-scroll-direction="horizontal" data-scroll-speed="9">
      - Sam Victor
    </h2>
  </section>
</template>

<style scoped>
section {
  background-color: black;
  color: white;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
h1 {
  font-size: 2.5rem;
  padding-bottom: 3rem;
}

h2 {
  color: darkgrey;
}

.appreciation-text {
  opacity: 0;
}

.animate {
  opacity: 1;
  transition: opacity 4s;
}
</style>
