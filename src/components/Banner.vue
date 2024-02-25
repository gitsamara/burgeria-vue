<template>
  <div id="main-banner">
    <h1>Burgeria.vue</h1>
  </div>
</template>
  
  <script>
export default {
  name: "Banner",
};
</script>
  
  <style scoped>
#main-banner {
  background-image: url("/public/img/burger.jpg");
  background-position: 0 -370px;
  background-size: cover;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 60px;
  padding: 20px 40px;
}
</style>