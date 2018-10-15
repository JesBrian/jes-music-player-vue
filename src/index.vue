<template>
  <div class="music-player">
    <div class="music-player-body">
      <div class="music-player-pic">
      </div>

      <div class="music-player-info">
        <div class="music-player-info-title">Title</div>
        <div class="music-player-info-lyric">Lyric</div>
        <div class="music-player-info-controller">Controller</div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'JesMusicPlayerVue'
  }
</script>

<style scoped>
  .music-player {
    width:100%; height:auto; border-radius:3px; box-shadow:0 1px 6px -1px rgba(0, 0, 0, 0.8);
  }

  .music-player-body {
    display:flex;
  }

  .music-player-pic {
    width:66px; height:66px; margin:1px; border-radius:2px;
    background:url(http://p1.music.126.net/kaISxJU3yP0Qvw6H_vUyAQ==/18984167765401316.jpg?param=180y180) 100% 100% no-repeat;
    background-size:cover;
  }

  .music-player-info {
    padding:0 12px 0 10px;
    flex:1; border-radius:2px;
    display:flex; flex-direction:column;
  }
  .music-player-info-title {
    flex:1; display:flex; align-items:center; text-indent:2em; background:lightgreen;
  }
  .music-player-info-lyric {
    flex:1; background:lightpink;
  }
  .music-player-info-controller {
    height:20px; background:lightskyblue;
  }
</style>
