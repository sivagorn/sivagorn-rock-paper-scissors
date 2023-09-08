<template>
  <div id="app">
    <h1>เกมเป่ายิ้งฉุบ</h1>
    <GameComponent />
  </div>
</template>

<script>
import GameComponent from './components/game.vue';

export default {
  components: {
    GameComponent,
  },
};
</script>

<style>

#app {
  text-align: center;
  color: #e4ffe6;
  font-size: 30px;
  text-shadow: 2px 2px 2px black;
  margin-top: 0px;
  background-color: #9fb1a9;
  width: 70%; 
  height: 110vh; 
  display: flex;
  flex-direction: column;
}

h1 {
  font-size: 4em;
}

.player1-name {
  color: #ff5b5b; 
  text-shadow: 2px 2px 2px black;
  font-size: 40px;
}

.player2-name {
  color: #7b65fd; 
  text-shadow: 2px 2px 2px black;
  font-size: 40px;
}


.player-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}

.reset-button {
  margin-left: 70px; 
  background-color: #00a957; 
  color: #fff; 
  font-size: 25px;
  border-radius: 30px;
  border: 5px solid #ffffff;  
}

.reset-button:hover {
  background-color: #008c47; 
}
.round-button:hover {
  background-color: #b10202ee; 
}

.round-button {
  
  background-color: #e70707; 
  color: #fff;
  font-size: 25px;
  border-radius: 30px;
  border: 5px solid #ffffff;  
}

.score-container {
  background-color: #f7f6f6; 
  color: #ff7cff; 
  font-size: 30px;
  padding: 3px; 
  margin-top: 15px; 
  text-align: center; 
  border-radius: 30px; 
  border: 2px solid #ff8742; 
  border-width: 10px;
  max-width: 400px; 
  margin: 20px auto;
}

.score-text {
  margin: 0; 
}
</style>



