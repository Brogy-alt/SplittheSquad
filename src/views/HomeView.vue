<template>
  <div>
    <NavbarC/>
  <main>
    <section id="about">
            <div class="home">
           
      <div class="home container d-flex align-items-center justify-content-center">
        <div class="row">
            <div class="col landing-text text-light" style="padding-top: 19rem; ">
                <h1>Embrace the Unexpected. Conquer The Field</h1>
            </div>
        </div>
    </div>
</div>
      </section>
    </main>

    <div>
    <PlayersC :player="playerData" />
  </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import NavbarC from '@/components/NavbarC.vue';
import PlayersC from '@/components/PlayersC.vue';

export default {
  name: 'HomeView',
  components: {
      NavbarC, PlayersC
  },
  data() {
    return {
      playerData: {
        name: 'Lionel Messi',
        image: ' messi',
        club: 'Paris Saint-Germain',
        position: 'Forward',
      }}
      
    },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Alegreya+Sans+SC:wght@700&display=swap');
main {
  min-height: 100vh;
  background: 
  url(https://i.postimg.cc/ZRQ9Zgzx/soccer-ball-through-net.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: auto;
 
}

.landing-text{
  font-family: 'Alegreya Sans SC', sans-serif;
}

</style>
