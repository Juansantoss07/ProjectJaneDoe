<script>
export default {
  name: "MyPortfolio",
};
</script>

<template>
  <div class="title" id="port">
    <h1>My Portfolio</h1>
  </div>
  <div class="container-port">
    <div class="img-port1">
      <img src="/public/img/wedding.jpg" alt="" />
      <img src="/public/img/rocks.jpg" alt="" />
      <img src="/public/img/sailboat.jpg" alt="" />
    </div>
    <div class="img-port2">
      <img src="/public/img/underwater.jpg" alt="" />
      <img src="/public/img/chef.jpg" alt="" />
      <img src="/public/img/weddingone.jpg" alt="" />
      <img src="/public/img/p6.jpg" alt="" />
    </div>
  </div>
</template>

<style lang="scss" scoped>

.container-port{

    display: flex;
    flex-direction: row;
    justify-content: center;

    .img-port1, .img-port2 {
  display: flex;
  flex-direction: column;
  width: 45%;
  padding: 1rem;
}

.img-port1{
  padding-left: 0;
}

.img-port2{
  padding-right: 0;
  padding-left: 0;
}

.img-port1 img, .img-port2 img {
  margin: 0.5rem 0;
}
}

@media(max-width:600px){
  .container-port{
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
    .img-port1, .img-port2{
      width: 100%;
      padding: 1rem;
    }
  }
}
</style>