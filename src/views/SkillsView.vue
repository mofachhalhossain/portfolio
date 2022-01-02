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
          headerBack="HTML"
          footerBack=""
          back="Most of the HTML5 topics"
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/css3.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="CSS"
          footerBack=""
          back="Css3 components, basics of Css animation and more"
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/javascript--v1.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Javascript"
          footerBack=""
          back="DOM manipulation, event handling, Async/Await, Promises, AJAX, JSON etc."
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Tailwind-CSS"
          footerBack=""
          back="Tailwind components, utilities, responsive design etc."
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://vuejs.org/images/logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Vue"
          footerBack=""
          back="Vue components, directives, routing, vuex."
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/java-coffee-cup-logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Java"
          footerBack=""
          back="Java basics, OOP, collections, generics etc."
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://hibernate.org/images/hibernate-logo.svg"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Hibernate"
          footerBack=""
          back="Hibernate basics, annotations, JPA, Hibernate ORM."
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/spring-logo.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Spring Framework"
          footerBack=""
          back="Spring MVC, spring jdbc, spring security, Rest Api."
          textSizeBack="1rem"
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
          headerBack="MySQL"
          footerBack=""
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/postgreesql.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="PostgreSQL"
          footerBack=""
          textSizeBack="1rem"
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
          headerBack="Git"
          footerBack=""
          back="All git topics"
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://img.icons8.com/color/480/000000/github.png"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Github"
          footerBack=""
          back="All github topics"
          textSizeBack="1rem"
          >
      </vue-flashcard>
      <vue-flashcard 
      headerFront=""
          imgFront="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg"
          colorBack="rgba(255, 255, 255, .15)"
          footerFront=""
          textSizeFront="0rem"
          colorFront=""
          headerBack="Postman"
          footerBack=""
          textSizeBack="1rem"
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
          headerBack="Thunderclient"
          footerBack=""
          textSizeBack="1rem"
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