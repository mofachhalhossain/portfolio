<template>
  <div class="upper_chunck">
    <VueWriter :array="arr" :start="1000" :typeSpeed="70" :eraseSpeed="80" :delay="1000"/>
  </div>
  <div class="lower_chunck">
    <label class="name">{{ name }}</label><br><br>
    <label class="info">Learning & Working On Full Stack Technologies</label>
  </div>
</template>

<script>
export default {
  name: 'MainView',
  data() {
      return { arr: ["Hi!", "I'm"], name: 'Mofachhal Hossain', }
    },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Caveat:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&display=swap');
.upper_chunck{
  font-family: 'Caveat', cursive;
  font-size: 56px;
  color: #ffff;
  margin-top: 17%;
}

.name{
  color: rgb(233, 15, 15);
  font-family: 'Lobster', cursive;
  font-size: 56px;
}

.info{
  /* color: #ffff; */
  font-family:'Roboto Mono', monospace;
  font-size: 24px;
  /* text-shadow: 0 0 5px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #ff00de, 0 0 70px #ff00de, 0 0 80px #ff00de, 0 0 100px #ff00de, 0 0 150px #ff00de; */
  color: #fff;
  text-shadow:
    0 0 2px #fff,
    0 0 5px #fff,
    0 0 8px #fff,
    0 0 15px #0ff,
    0 0 25px #0ff,
    0 0 30px #0ff,
    0 0 40px #0ff,
    0 0 50px #0ff;
}

@media screen and (max-width: 768px) {
  .upper_chunck{
    font-size: 40px;
    margin-top:13rem;
    margin-left: -1rem;
  }
}

@media screen and (max-width: 576px) {
  .upper_chunck{
    margin-top:11rem;
    margin-left: -1rem;
  }
}

@media screen and (max-width: 480px) {
  .upper_chunck{
    margin-top:9rem;
    margin-left: -1rem;
  }
  .name{
    font-size: 42px;
  }
}
</style>
