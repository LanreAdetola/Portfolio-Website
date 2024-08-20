<template>
    <div class="wrapper">
        <div class="main-container">

            <div class="container-one">

            <div class="profile">
        <img src="../assets/profilepic.png" alt="">
        <h3>Lanre Adetola</h3>
        <p>Software Developer</p>
    </div>

    <div class="social-links">

            <div class="link">
                <a href="https://github.com/LanreAdetola" target="_blank">
                    <img src="../assets/icons8-github-64.png" alt="">
                    <h2>GitHub</h2>
                </a>
               
            </div>
            <div class="link">
                <a href="https://linkedin.com/in/lanre-adetola0" target="_blank">
                    <img src="../assets/icons8-linkedin-64.png" alt="">
                    <h2>LinkedIn</h2>
                </a>
                

            </div>
        </div>
</div>


    <div class="container-two">
        <div class="about-me">
            <h1>About Me</h1>
                <p>
                    I am currently a <strong class="highlight">2<sup>nd</sup> year</strong> student pursuing a professional bachelor's degree in <span class="highlight">Information Management & Multimedia</span> at <strong class="highlight">Thomas More University</strong> (Belgium).
                    <br><br>
                    My specialization is in <span class="highlight">Data Science, Security & Protection</span>, equipping me with the skills and knowledge to navigate complex digital environments.
                    <br><br>
                    I am also gaining invaluable experience under the mentorship of <span class="mentor">Collin Van der Vorst</span>, an accomplished Fullstack Developer.
                </p>
        </div>


        <div class="Technology-section">
            <h1>Technologies Studied</h1>
                <div class="logos">
                <img src="../assets/icons8-html-64.png" alt="">
                <img src="../assets/icons8-css-64.png" alt="">
                <img src="../assets/icons8-javascript-64.png" alt="">
                <img src="../assets/icons8-vue-js-64.png" alt="">
            </div>
        </div>
    <div class="button-container">
        <div class="projects-button">
            <a href="">My Projects</a>
        </div>
            <div class="projects-button">
                    <a href="">My Resume</a>
            </div>
            </div>
        </div>
    </div>
</div>
    
    
</template>

<script> 
export default {

}

</script>

<style scoped>

.wrapper{
    display: flex;
    justify-content: center;
}

img{
    height: 20px;
}

.main-container{
    display: flex;
    flex-direction: row;
    background-color: #cecece;
    border-radius: 25px;
    width: 60%;
    background-color: #A0D4FF;

}

.container-one{
    background-color: #1292EE;
    padding: 2.5%;
    width: 30%;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;

}

.profile img{
    height: 10rem;
    border-radius: 50%;
}

.link a{
    text-decoration: none;
    color: #2c3e50;
    font-size: 10px;
}

.link img{
    height: 2rem;
}

.container-two{
    margin: 2.5%;
    width: 70%;
}

.about-me{
    text-align: left;
    margin: 2.0%;
    width: 85%;
}

.logos img {
    height: 2.5rem;
}

.button-container{
    margin-top: 5%;
    display: flex;
    flex-direction: center;
    justify-content: center;
    align-items: center;

}

.projects-button{
    background-color: #005CA4;
    border-radius: 15px;
    padding: 5px;
    margin: 5px;
}

.projects-button a{
    text-decoration: none;
    color: #fff;
}

.highlight {
    color: #FF6347; /* Example: Tomato color */
    font-weight: bold;
}

.mentor {
    font-weight: bold;
    font-style: italic;
    color: #1292EE; /* Matches your container-one background color */
}

@media only screen and ( max-width: 950px){
    .main-container{
        width: 95%;
    }
}
    
</style>