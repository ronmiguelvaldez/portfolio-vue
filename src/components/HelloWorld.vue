<template>
    <div class="header">
      <h1> My Name</h1>
      <img src="@/assets/man.jpg" alt="man">
    </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.header {
  background-color: #111;
  min-height: 100vh;
  color: #fff;
}
h1 {
  font-size: 2em;
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
img {
  max-width: 500px;
  width: 50%;
  transform: scale(.95);
  filter: blur(5px);
  transition: .5s;
  animation: img 1.5s; 
}
img:hover {
  filter: blur(0);
  transform: scale(1);
}
/*@keyframes img {
  from{filter: blur(100px);}
  to{filter: blur(0);}
}*/
</style>
