<template>
  <div class="container">
    <Navbar/>
    <Grid/>
    <span class="line"></span>
    <Content/>
    <span class="line"></span>
    <List/>
    <span class="line"></span>
    <Avatar/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
body {
  height: 300vh;
}
span {
  display: block;
  width: 80;
  height: 1px;
  background-color: black;
  margin-top: 5rem;
}

#garis {
  margin-top: 5rem;
}
</style>
