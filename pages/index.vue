<template>
  <div id="start_menu">
    <GameButtons />
  </div>
</template>

<script>
import GameButtons from '../components/GameButtons.vue';
export default {
  components: {
    GameButtons,
  },
};
</script>

<style>
.buttons {
	display: flex;
	justify-content: center;
	align-content: center;
}
</style>
