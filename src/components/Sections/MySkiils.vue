<script>
export default {
  name: "MySkills",
};
</script>

<template>
  <div class="content-skills">
    <div class="title">
      <h1>My Skills</h1>
    </div>
    <div class="skills">
      <p>Photography</p>
      <div class="box-skills">
        <div class="percentage1">95%</div>
      </div>
    </div>
    <div class="skills">
      <p>Web Design</p>
      <div class="box-skills">
        <div class="percentage2">85%</div>
      </div>
    </div>
    <div class="skills">
      <p>Photoshop</p>
      <div class="box-skills">
        <div class="percentage3">80%</div>
      </div>
    </div>
    <div class="box-numbers">
      <div class="numbers-skills">
        <div>
          <p class="pnumber">14+</p>
          <p>Partnes</p>
        </div>
        <div>
          <p class="pnumber">55+</p>
          <p>Projects Done</p>
        </div>
        <div>
          <p class="pnumber">89+</p>
          <p>Happy Clients</p>
        </div>
        <div>
          <p class="pnumber">150+</p>
          <p>Meetings</p>
        </div>
      </div>
    </div>

    <div class="resume">
      <button><i class="bi bi-download"></i> Download Resume</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.content-skills {
  display: flex;
  flex-direction: column;
  width: 100%;
  justify-content: space-evenly;

  .skills {
    display: flex;
    flex-direction: column;
    padding: 1rem 2rem;

    p {
      font-size: 15px;
      color: #757575;
      margin-bottom: 1rem;
    }
    .box-skills {
      background: #cccccc;

      .percentage1 {
        background: #616161;
        padding: 0.5rem;
        width: 95%;
        color: #fff;
        display: flex;
        justify-content: center;
      }
      .percentage2 {
        background: #616161;
        padding: 0.5rem;
        width: 85%;
        color: #fff;
        display: flex;
        justify-content: center;
      }
      .percentage3 {
        background: #616161;
        padding: 0.5rem;
        width: 80%;
        color: #fff;
        display: flex;
        justify-content: center;
      }
    }
  }
  .box-numbers {
    width: 100%;
    display: flex;
    justify-content: center;
    padding: 2rem;

    .numbers-skills {
      background: #616161;
      width: 100%;
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 2.5rem 1rem;
      color: #fff;
      text-align: center;

      .pnumber {
        font-size: 24px;
      }

      p {
        font-size: 15px;
      }
    }
  }

  .resume {
    padding: 1rem 2rem;
  }
}

@media(max-width:600px){
  .numbers-skills{
    flex-direction: column;

    .pnumber{
      padding: 1rem 0;
    }
  }
}
</style>