<template>
  <img
    class="PartsLogo"
    alt="Parts Sistemas"
    src="LogoContorno.svg"
  >
</template>

<style>
.PartsLogo {
  width: 20vmax;
  transform: rotateY(560deg);
  animation: turn 3.5s ease-out forwards 0.2s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
