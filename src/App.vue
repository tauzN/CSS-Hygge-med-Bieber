<template>
  <div id="bg">
    <Navbar />
    <div id="card">
      <Login />
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Login from "./components/Login";

export default {
  name: "App",
  components: {
    Navbar,
    Login,
  },
};
</script>

<style>
a {
  text-decoration: none;
  color: black;
}
#bg {
  background-image: url("./assets/HQ.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
}
#card {
  background-color: rgba(255, 255, 255, 0.8);
  height: 90vh;
  width: 90vw;
  margin: 20px auto;
  border-radius: 50px;
  box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.2);
  padding: 100px;
}
</style>
