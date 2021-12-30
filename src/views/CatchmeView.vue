<template>
<div class="catch">
    <a href="http://github.com/mofachhalhossain">
    <i class="fab fa-github"></i>
    </a>
    <a href="https://codepen.io/mofachhalhossain">
        <i class="fab fa-codepen"></i>
    </a>
    <a href="mailto:http://mofachhalhossain101@gmail.com">
        <i class="fas fa-envelope-open"></i>
    </a>
    <a href="https://www.linkedin.com/in/mofachhal-hossain-2328121bb/">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://wa.me/+8801732303731">
        <i class="fab fa-whatsapp"></i>
    </a>
</div>
    
</template>

<script>

</script>

<style>
.catch {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 18rem;
}
.catch a{
    color: #fff;
    margin: 0 2rem;
    font-size: 8rem;
}
.catch a:hover{
    color: rgb(219, 15, 15);
    text-decoration: none;
}
@media screen and (max-width: 940px) {
    .catch {
        margin-top: 20rem;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-gap: 2rem;
    }
    .catch a{
        font-size: 4rem;
    }
}
@media screen and (max-width: 556px) {
    .catch {
        margin-top: 18rem;
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 2rem;
    }
    .catch a{
        font-size: 4rem;
    }
}
</style>