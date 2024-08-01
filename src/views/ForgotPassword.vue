<script setup>
import Home from "./HomeView.vue";
</script>

<template>
    <Home />
    <section class="container">
      <div class="login-container">
        <div class="circle circle-one"></div>
        <div class="form-container">
          <img
            src="../assets/teacher_3d1.png"
            alt="illustration"
            class="illustration"
          />
          <h1 class="opacity">FORGOT PASSWORD</h1>
          <form>
            <input type="email" placeholder="email" v-model="userName"/>
            <button type="button" class="opacity" @click="updateMessage">SUBMIT</button>
          </form>
          <!-- <div class="register-forget opacity">
            <a href="/register">REGISTER</a>
            <a href="">FORGOT PASSWORD</a>
          </div> -->
        </div>
        <div class="circle circle-two"></div>
      </div>
      <div class="theme-btn-container"></div>
    </section>
</template>

<script>
export default {
  data() {
    return {
        userName: '',
        password: ''
    }
  },
  methods: {
    updateMessage() {
      console.log(this.userName, this.password);
    },
  }
}
</script>

<style scoped>

</style>
