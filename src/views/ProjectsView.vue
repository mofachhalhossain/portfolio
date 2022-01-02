<template>
<div class="title">
  Some of my pet projects
</div>
<div class="animated flipInX flashcard">
  <div class="projects">
    <div class="background">
          <div class="card">
              <img src="@/img/springboot-todo.png" />
              <div class="card_body">
                <div class="proj_title">Springboot To-Do application</div>
              <div class="description">
                Users need to register/login with email and password which is controlled by hibarnate authentication. After login user will be able to see role, dashboard, create/update/delete tasks.
              </div>
              <div class="stack">Spring MVC, Spring JDBC, Hibernate, CRUD, Postgresql</div>
              </div>
              <div class="card_link" >
                <a href="https://github.com/mofachhalhossain/SpringBoot-Postgres-ToDo">Github</a>
                <a href="https://springboot-postgress-todo.herokuapp.com/">Live</a>
              </div>
          </div>
    </div>

    <div class="background">
          <div class="card">
              <img src="@/img/portfolio.png" />
              <div class="card_body">
                <div class="proj_title">Vue-Portfolio</div>
              <div class="description">My portfolio site in Vue3.</div>
              <div class="stack">Vue3, Vue-router, Vue-writter, Vue-particles-bg, Fontawesome</div>
              </div>
              <div class="card_link" style="margin-top: 3.2rem">
                <a href="https://github.com/mofachhalhossain/portfolio">Github</a>
                <a href="#">Live</a>
              </div>
          </div>
    </div>

    <div class="background">
          <div class="card">
              <img src="@/img/javascript-repo.png" />
              <div class="card_body">
                <div class="proj_title">Users-Github</div>
              <div class="description">User's avatar, info and repositories from github api</div>
              <div class="stack">Javascript, Github-API</div>
              </div>
              <div class="card_link" style="margin-top: 3.9rem">
                <a href="https://github.com/mofachhalhossain/Visit_Github_Profiles">Github</a>
                <a href="https://mofachhalhossain.github.io/Visit_Github_Profiles/">Live</a>
              </div>
          </div>
    </div>

    <div class="background">
          <div class="card">
              <img src="@/img/vue-repoissue.png" />
              <div class="card_body">
                <div class="proj_title">Github-Repo-Issue</div>
              <div class="description">Visualization of github repo issues using Vue D3 and github api</div>
              <div class="stack">Vue3, D3, Axios, Github api</div>
              </div>
              <div class="card_link" style="margin-top: 3.2rem">
                <a href="https://github.com/mofachhalhossain/Repo_Issue_Data_Vue3">Github</a>
                <a href="https://mofachhalhossain.github.io/Repo_Issue_Data_Vue3/">Live</a>
              </div>
          </div>
    </div>

    <div class="background">
          <div class="card">
              <img src="@/img/responsive-ui.png" />
              <div class="card_body">
                <div class="proj_title">Responsive Ui</div>
              <div class="description">Simple Responsive UI</div>
              <div class="stack">Html5 & Css3</div>
              </div>
              <div class="card_link" style="margin-top: 3.9rem">
                <a href="https://github.com/mofachhalhossain/Fake_Host">Github</a>
                <a href="https://mofachhalhossain.github.io/Fake_Host/">Live</a>
              </div>
          </div>
    </div>
  </div>
</div>
</template>

<script>
export default{
  
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');
.title{
  color: #ffff;
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 0;
  margin-top: 2rem;
  justify-content: center;
}

.projects{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 2fr));
  grid-gap: 1rem;
  margin-top: 2rem;
  margin-left: 2rem;
}
.background {
    height: 100%;
    padding: 10px;
    border-radius: 10px;
}
  
.card {
    margin-right: auto;
    margin-left: auto;
    width: 250px;
    height: 350px;
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.527);
    border-radius: 10px;
    backdrop-filter: blur(14px);
    background-color: #53525200;
    padding: 10px;
    text-align: center;
}
.card:hover {
    box-shadow: 0 15px 25px rgba(129, 124, 124, 0.2);
    width: 260px;
    height: 360px;
}
  
.card img {
    height: 60%;
    width: 100%;
}

.card_body {
  margin-top: 1.4rem;
  color: #ffff;
}

.card_link {
  font-family: 'Oswald', sans-serif;
  margin-top: .7rem;
  display: flex;
  justify-content: space-between;
  
}
.card_link a{
  text-decoration: none;
  color: #ffff;
  font-size: 1rem;

}
.card_link a:hover{
  color: rgb(233, 35, 35);
}

.proj_title{
  margin-top: -1.2rem;
  font-size: 1rem;

}
.description{
  font-size: .7rem;
  margin-top: .4rem;
}
.stack{
  font-size: .7rem;
  margin-top: .4rem;
  color: rgb(245, 60, 60);
}

.animated {
    animation-duration: 1s;
    animation-fill-mode: both;
}
@keyframes flipInX {
    from {
        transform: perspective(100px) rotate3d(1, 0, 0, 90deg);
        animation-timing-function: ease-in;
        opacity: 0;
    }
    40% {
        transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
        animation-timing-function: ease-in;
    }
    60% {
        transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
        opacity: 1;
    }
    80% {
        transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
    }
    to {
        transform: perspective(400px);
    }
}
.flipInX {
    backface-visibility: visible !important;
    animation-name: flipInX;
}
@media screen and (max-width: 373px) {
  .title{
    font-size: 1.5rem;
  }
  .projects{
    margin-left: 0;
  }
  .card{
    width: 100px;
    height: 150px;
    border-radius: 0;
    padding: 0;
  }
  .background{
    padding: 0;
    border-radius: 0;
  }
}

</style>
