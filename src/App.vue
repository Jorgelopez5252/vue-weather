<template>
  <div id="app">
    <!-- inner piece of app -->
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search.."/>
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      api_key: 'a511288c93ca905f4ba9b1a0eda9231d'
    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

#app {
  background-image: url(./assets/cold-bg.jpg);
}
</style>
