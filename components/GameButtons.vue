<template>
  <div>
    <button @click="startGame">Iniciar Jogo</button>
    <button @click="exitGame">Sair</button>
    <button @click="showScore">Ver Placar</button>
  </div>
</template>

<script>
export default {
  methods: {
    startGame() {
      // Lógica para iniciar o jogo
      this.$router.push("game");
    },
    exitGame() {
      // Lógica para sair do jogo
      this.$router.push("end");
    },
    showScore() {
      // Lógica para exibir o placar
      this.$router.push("leaderboard");
    },
  },
};
</script>
