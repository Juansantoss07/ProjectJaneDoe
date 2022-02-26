<script>
export default {
  name: "About",
};
</script>

<template>
  <div class="content-about">
    <div class="title">
      <h1>About</h1>
    </div>
    <hr>
    <div class="text-about">
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempora
        perferendis esse harum vel quos aperiam quaerat, maiores modi vero illo
        consequatur nulla consectetur quas, fuga at voluptatibus velit, magnam
        facere! Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, numquam harum iusto odit assumenda, debitis nemo possimus cum, sint ipsum iure provident obcaecati magni error est accusantium beatae perspiciatis unde. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quis nihil odio eos a aperiam illo sit ratione commodi, voluptatibus, repellendus, sed quas exercitationem. Necessitatibus explicabo hic delectus ullam distinctio asperiores.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>


    hr{
        margin: 0 2rem;
        border-color: #dfdede;
        opacity: .4;
        border-style: solid;
    }
    .content-about{
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        
        .text-about{
            padding: 1rem 0;
            display: flex;
            width: 100%;
            align-items: center;
            justify-content: center;

            p{
                padding: 0 2rem;
            }
        }
    }


</style>