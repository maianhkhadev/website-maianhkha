<template>
  <div class="link link--nukun" href="#"><span>M</span>ai <span>A</span>nh <span>K</span>ha</div>
</template>

<style lang="scss" scoped>
  .link--nukun {
  	color: #ffffff;
  	text-transform: uppercase;
  	transition: color 0.3s;
    overflow: hidden;
  }
  .link--nukun:hover {
  	color: #b1c0b2;
  }
  .link--nukun span {
  	display: inline-block;
  	position: relative;
  	transform: perspective(1000px) rotate3d(0, 1, 0, 0deg);
  	transition: transform 0.5s, color 0.5s;
  	transition-timing-function: cubic-bezier(0.2, 1, 0.3, 1);
  }
  .link--nukun:hover span {
    color: #ffffff;
  	transform: perspective(1000px) rotate3d(0, 1, 0, 180deg);
  }
</style>
