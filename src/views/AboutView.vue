<template>
  <div class="about">
    <h3>About Dino Todo</h3>
    <br>
    <p>
      This is a simple todo app built with Vue 3 and Vite. It uses the
      composition API and the new <code>setup()</code> syntax, the todos are saved in localstorage(). Also with the help of some extensions. This was my first FE project.
    </p>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    align-items: center;
    line-height: 1.5;
    padding: 50vh;
  }
}

.about {
  text-align: center;
  padding: 25px;
  line-height: 1.5;
}
</style>
