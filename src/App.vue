<script>
import SidebarImg from "./components/SidebarImg/SidebarImg.vue";
import SpaceRight from "./components/SpaceRight/SpaceRight.vue";
export default {
  components: {
    SidebarImg,
    SpaceRight,
  },
};
</script>

<template>
  <div class="home">
    <SidebarImg />
    <SpaceRight />
  </div>
</template>

<style lang="scss">

.home {
  display: flex;
  flex-direction: row;
}

.title {
  display: flex;
  justify-content: flex-start;
  padding: 1rem 2rem;

  h1 {
    color: #757575;
    font-size: 30px;
  }
}

        button{
            padding: 1rem 1.5rem;
            border: none;
            background: #f1f1f1;
            font-size: 15px;
            font-weight: 300;
            cursor:pointer;

            i{
                font-size: 18px;
                padding-right: .5rem;
            }
        }

        button:hover{
          background: #CCCCCC;
        }


</style>