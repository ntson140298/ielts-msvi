<script setup>

</script>

<template>
  <main>
    <div class="container-header">
      <div class="logo">
        <a href="/">
          <img src="../assets/logo.png" alt="logo" srcset="" width="150" />
        </a>
      </div>
      <div class="right-content">
        <div class="about r-20">
          <router-link to="/about">
            <h2>About</h2>
          </router-link>
        </div>
        <div class="document r-20">
          <router-link to="/document">
            <h2>Document</h2>
          </router-link>
        </div>
        <div class="login">
          <router-link to="/login">
            <h2>Login</h2>
          </router-link>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
  .container-header {
    display: flex;
    justify-content: space-between;
  }
  .right-content {
    display: flex;
  }
</style>