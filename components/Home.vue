<template>
  <div class="main">
    <Mainheader />
    <h1>Create Amezing Website Pure HTML & CSS Only</h1>
    <button class="btn">Learn More</button>
    <button class="btn1">Subscribe</button>
  </div>
</template>

<script>
export default {}
</script>

<style>
.main {
  background-image: url('https://image.shutterstock.com/image-photo/old-brick-black-color-wall-260nw-1605128917.jpg');
  background-size: cover;
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;

  /* background-origin: border-box; */
  border: rgb(243, 72, 100) 10px solid;

  text-align: center;
}
.btn {
  color: white;
  border: white 1px solid;
  background-color: transparent;
  margin-top: 15%;
  margin-left: -5%;
  font-size: 25px;
  height: 8%;
  width: 20%;
  font-weight: bold;
  border-radius: 15px;
}
.btn1 {
  color: black;
  border: white 1px solid;
  background-color: white;
  margin-top: 15%;
  margin-left: 5%;
  font-size: 25px;
  height: 8%;
  width: 20%;
  font-weight: bold;
  border-radius: 15px;
}
h1 {
  color: white;
  color: white;
  text-align: center;
  position: relative;
  top: 25%;
  font-size: 80px;
  padding-left: 10%;
  padding-right: 10%;
  text-shadow: 0 0 5px rgb(223, 3, 39);
}
</style>