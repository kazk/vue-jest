<template>
  <div :class="$style.testClass">
    <div class="a" />
  </div>
</template>

<style module src="./styles/external.css" />

<style module="css">
.a {
  background: color(red a(90%));
}
</style>
