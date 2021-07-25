<template>
  <div>
    <h1 class="a">A</h1>
    <h1 class="b">B</h1>
    <h1 class="c">C</h1>
    <h1 class="d">D</h1>
    <h1 class="e">E</h1>
    <h1 class="f">F</h1>
    <h1 class="g">G</h1>
  </div>
</template>

<style scoped>
div {
  display: flex;
  justify-content: center;
  }

.a {
  animation: animation 1s ease infinite alternate;
}

.b {
  animation: animation 1s ease infinite alternate;
  animation-delay: 0.1s;
}

.c {
  animation: animation 1s ease infinite alternate;
  animation-delay: 0.2s;
}

.d {
  animation: animation 1s ease infinite alternate;
  animation-delay: 0.3s;
}

.e {
  animation: animation 1s ease infinite alternate;
  animation-delay: 0.4s;
}

.f {
  animation: animation 1s ease infinite alternate;
  animation-delay: 0.5s;
}

.g {
  animation: animation 1s ease infinite alternate;
  animation-delay: 0.6s;
}
@keyframes animation {
  0% {transform: translateY(0px);}
  100% {transform: translateY(-10px);}
}
</style>