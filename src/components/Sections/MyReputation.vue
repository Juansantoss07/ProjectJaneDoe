<script>
export default {
  name: "MyReputation",
};
</script>

<template>
  <div class="content-reput">
    <div class="title">
      <h1>My Reputation</h1>
    </div>

    <div class="info-reput">
      <div class="person">
        <div class="profile-img">
          <img src="/public/img/avatar_smoke.jpg" alt="" />
        </div>
        <div class="box-info">
          <div class="name-person">
            <h4>Chandler Bing.</h4>
            <p>Web Designer.</p>
          </div>
          <div class="des-person">
            Jane Doe is just awesome. I am so happy to have met her!
          </div>
        </div>
      </div>
      <div class="person">
        <div class="profile-img">
          <img src="/public/img/bandmember.jpg" alt="" />
        </div>
        <div class="box-info">
          <div class="name-person">
            <h4>Chris Fox</h4>
            <p>CEO at Mighty Schools.</p>
          </div>
          <div class="des-person">Jane Doe saved us from a web disaster.</div>
        </div>
      </div>
      <div class="person">
        <div class="profile-img">
          <img src="/public/img/avatar_g2.jpg" alt="" />
        </div>
        <div class="box-info">
          <div class="name-person">
            <h4>Chris Fox</h4>
            <p>CEO at Mighty Schools.</p>
          </div>
          <div class="des-person">Jane Doe saved us from a web disaster.</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.content-reput {
  display: flex;
  flex-direction: column;
  width: 100%;
  padding: 1rem 0rem;

  .info-reput{
      padding: 1rem 2rem;
  }

  .person {
    display: flex;
    padding: 2rem 0rem 0rem;
    justify-content: flex-start;
  }

  .profile-img {
    width: 15%;
    padding-right: 1rem;
  }

  .profile-img img {
    width: 100%;
    border-radius: 50px;
  }

  .box-info {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;

      p{
        width: 50%;
        margin-left: 1rem;
        color: #868686;
      }

      .des-person{
        color: #868686;
      }
    .name-person {
      display: flex;
      width: 100%;
      justify-content: flex-start;
      align-items: center;
    }

    .des-person{
      text-align: center;
    }
  }
}

@media(max-width:600px){
  .person{
    flex-direction: column;
    justify-content:center;
    align-items: center;

    .name-person{
      justify-content: center;
      align-items: center;
      flex-direction: column;

        p{
      width: 100%;
      text-align: center;
    }
    }
  }
   
}
</style>