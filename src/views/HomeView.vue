<template>
  <div>
    <NavbarC/>
  <main>
    <section id="about">
            <div class="home">
           
      <div class="home container d-flex align-items-center justify-content-center">
        <div class="row">
            <div class="col landing-text text-light" style="padding-top: 19rem; ">
                <h1>Cool words here</h1>
            </div>
        </div>
    </div>
</div>
      </section>
    </main>

    <div>

    <PlayerCards/>

  </div>

  <div>

<TeamSlection/>

</div>

    
  </div>
</template>

<script>

import NavbarC from '@/components/NavbarC.vue';
import PlayerCards from '@/components/PlayerCards.vue';
import TeamSlection from '@/components/TeamSlection.vue';

// import PlayersC from '@/components/PlayersC.vue';

export default {
  name: 'HomeView',
  components: {
      NavbarC, PlayerCards, TeamSlection
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Alegreya+Sans+SC:wght@700&display=swap');
main {
  
  min-height: 100vh;
  background: linear-gradient(rgba(255, 255, 255, 0.039), rgba(0, 0, 0, 1)), url(https://i.postimg.cc/FzLx4vxt/fifa-background-tqq9pxlhzeue8u6w.png) ;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: auto;
 
}

.landing-text{
  font-family: 'Alegreya Sans SC', sans-serif;
}

</style>
