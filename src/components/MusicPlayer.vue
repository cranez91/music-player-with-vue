<template>
  <div class="player">
    <div class="cover">
      <img src="../assets/vinyl.png" alt="logo"/>
    </div>
    <div class="info">
      <div class="title">
        Armee der tristen 
      </div>
      <div class="singer">
        Rammstein
      </div>
    </div>
    <div class="volume-box">
      <span class="volume-down">
        <i class="material-icons">remove</i>
      </span>
      <input type="range" class="volume-range" step="1" value="0" max="100">
      <span class="volume-up">
        <i class="material-icons">add</i>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MusicPlayer',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 
</style>
