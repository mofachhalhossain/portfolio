<template>
<div class="welcome">
  <VueWriter :array="arr" :start="2000" :typeSpeed="200" :delay="3000"/>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
      return { arr: ["Welcome",] };
    },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Caveat:wght@700&display=swap');
.welcome{
  font-family: 'Caveat', cursive;
  font-size: 56px;
  color: #ffff;
  margin-top: 20%;
}
@media screen and (max-width: 768px) {
  .welcome{
    font-size: 40px;
    margin-top: 60%;
    margin-left: -1rem;
  }
}
</style>
