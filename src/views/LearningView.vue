<template>
    <div class="learning">
        <div class="title_first">
        <label>Javascript:</label>
    </div>
    <div class="description">
        <ul>
            <li><span>.</span>Advanced javascript</li>
            <li><span>.</span>Node Js</li>
            and more...
        </ul>
    </div>
    <div class="title_other">
        <label>Spring:</label>
    </div>
    <div class="description">
        <ul>
            <li><span>.</span>Spring Boot Actuator</li>
            <li><span>.</span>Testing in Spring Boot</li>
            <li><span>.</span>Spring Security</li>
            and more...
        </ul>
    </div>

    <div class="title_other">
        <label>Sass:</label>
    </div>
    <div class="description">
        <ul>
            <li>[In Queue]</li>
        </ul>
    </div>

    <div class="title_other">
        <label>Jquery:</label>
    </div>
    <div class="description">
        <ul>
            <li>[In Queue]</li>
        </ul>
    </div>

    <div class="title_other">
        <label>MongoDB:</label>
    </div>
    <div class="description">
        <ul>
            <li>[In Queue]</li>
        </ul>
    </div>
    </div>
</template>

<script>

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
.learning{
    margin-left: 2rem;
}
.title_first{
    font-family: 'Lobster', cursive;
    font-size: 3rem;
    margin-top: 4rem;
    margin-left: 12rem;
    color: rgb(233, 15, 15);
    display: flex;
    justify-content: flex-start;
}
.title_other{
    font-family: 'Lobster', cursive;
    font-size: 3rem;
    margin-top: 0;
    margin-left: 12rem;
    color: rgb(233, 15, 15);
    display: flex;
    justify-content: flex-start;
}
.description{
    display: flex;
    justify-content: flex-start;
    color: #ffff;
    margin-left: 26rem;
}
.description ul{
    margin-left: 0;
}
.description li{
    margin-left: 0;
    margin-top: 0;
    font-size: 1.5rem;
    display: flex;
    justify-content: flex-start;
    list-style-type: square;
}
.description span{
    margin-right: 1rem;
}

@media screen and (max-width: 940px) {
    .title-first{
    font-size: 3rem;
    margin-top: 4rem;
    margin-left: 2rem;
    color: rgb(233, 15, 15);
    display: flex;
    justify-content: flex-start;
    }
    
}

@media screen and (max-width: 790px) {
    .learning{
        margin-left: -4rem;
    }
    .title-first{
        margin-right: 4rem;
        font-size: 2rem;
    }
}

@media screen and (max-width: 692px) {
    .learning{
        margin-left: 8rem;
    }
    .title_first{
        margin-left: 1rem;
        margin-top: 2rem;
        font-size: 2.5rem;
    }
    .title_other{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 2.5rem;
    }
    .description{
        margin-left: 6rem;
    }
    .description ul{
        font-size: 1rem;
    }
    .description li{
        font-size: 1rem;
    }
}
@media screen and (max-width: 592px) {
    .learning{
        margin-left: 7rem;
    }
    .title_first{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 2rem;
    }
    .title_other{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 2rem;
    }
    .description{
        margin-left: 4rem;
    }
}

@media screen and (max-width: 436px) {
    .learning{
        margin-left: 4rem;
    }
    .title_first{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 1.5rem;
    }
    .title_other{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 1.5rem;
    }
    .description{
        margin-left: 1.5rem;
    }
    .description ul{
        font-size: 1rem;
    }
    .description li{
        font-size: 1rem;
    }
}

@media screen and (max-width: 375px) {
    .learning{
        margin-left: 2rem;
    }
    .title_first{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 1.5rem;
    }
    .title_other{
        margin-left: 0;
        margin-top: 2rem;
        font-size: 1.5rem;
    }
    .description{
        margin-left: 1rem;
    }
    .description ul{
        font-size: 1rem;
    }
    .description li{
        font-size: 1rem;
    }
    
}
</style>