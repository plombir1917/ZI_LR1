<template>
  <div class="vue">
    <main>
      <h1>Копич Захар АС-20</h1>
      <h2 align="center" style="margin-top: 15px">
        <nuxt-link to="/vigener"> Метод Виженера</nuxt-link>
      </h2>
      <h2 align="center" style="margin-top: 15px">
        <nuxt-link to="/gamma">Гаммирование</nuxt-link>
      </h2>
    </main>
  </div>
</template>

<style scoped>
.vue {
  font-family: 'Noto Sans', sans-serif;
  min-height: 100vh;
  color: whitesmoke;
  text-align: left;
}

nuxt-link,
h2 {
  text-decoration: none;
}

.container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: column;
  align-items: center;
}

input {
  border-radius: 10px;
  width: 500px;
  margin-top: 20px;
  text-align: left;
}

h2 {
  text-decoration: none;
}

h5 {
  margin-top: 10px !important;
  margin: 10px auto;
}
</style>
<style>
body {
  background-color: rgb(32, 32, 32);
}
</style>
