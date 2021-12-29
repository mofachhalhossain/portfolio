<template>
  <div class="about">
    <div class="lang">
      Languages & Frameworks
    </div>
    <div class="card_tech">
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/html-5--v1.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/css3.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/javascript--v1.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://vuejs.org/images/logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/java-coffee-cup-logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://hibernate.org/images/hibernate-logo.svg"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/spring-logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
    </div>
    <div class="lang">
      DB
    </div>
    <div class="card_tech">
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/mysql-logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/postgreesql.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
    </div>

    <div class="lang">
      Tools & Technologies
    </div>
    <div class="card_tech">
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/git.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/github.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>
      <div class="or">
        /
      </div>
      <vue-flashcard 
      headerFront=""
          imgFront="https://raw.githubusercontent.com/rangav/thunder-client-support/master/images/thunder-icon.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          >
      </vue-flashcard>

    </div>
  </div>
</template>


<script>
import vueFlashcard from 'vue-flashcard';
export default{
  components : { vueFlashcard }
}
</script>

<style scoped>
.lang{
  font-size: 2rem;
  font-weight: bold;
  color: #fff;
  text-align: center;
  margin-top: 2rem;
}
.card_tech{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin-top: 2rem;
}
.or{
  font-size: 10rem;
  font-weight: bold;
  color: #fff;
  text-align: center;
  margin-top: 2rem;
  cursor: none;
}
@media screen and (max-width: 600px) {
  .card_tech{
    flex-direction: column;
  }
  .or{
    font-size: 7rem;
  }
  
}
</style>