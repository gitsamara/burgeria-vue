<template>
  <div>
    <div id="nav">
      <router-link to="/" id="logo-url">
        <img :src="logo" :alt="alt" id="logo" />
      </router-link>
      <router-link to="/">Home</router-link> |
      <router-link to="/pedidos">Pedidos</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"],
};
</script>

<style scoped>
#nav {
  background-color: #fcba03;
  border-bottom: 4px solid #fff;
  padding: 5px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

#logo-url {
  margin: auto;
  margin-left: 0;
}

#logo {
  width: 40px;
  height: 40px;
}

a {
  color: #222;
  text-decoration: none;
  margin: 12px;
  transition: 0.5s;
}

a:hover {
  color: #fff;
}
</style>