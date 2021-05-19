<template>
    <header>
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
        <div class="header-cut"></div>
    </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
    position: absolute;
    width: 100vw;
    height: 111px;
    left: 85px;
    top: 0px;
    background: #15637B;
}

.header-cut {
    position: absolute;
    width: 289px;
    height: 20px;
    left: 60%;
    top: 91px;
    background: #0e546a;
    border-radius: 50px 50px 0px 0px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>