<template>
    <div class="main-container">
        <div class="project-card" v-for="(items,index) in projectData.ProjectsArray" v-bind:key="items">
            <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
            <img :src="projectData.ProjectsArray[index].Image" alt="">
            <p>{{ projectData.ProjectsArray[index].About }}</p>
            <div class="links">
                <a :href="projectData.ProjectsArray[index].Link1" target="_blank"><img src="../assets/icons8-github-64.png" alt=""></a>
            </div>

        </div>
    </div>

</template>

<script>
import jsonData from "/projects.json"

export default {
    data() {
        return{
            projectData: jsonData
        }
        
    }
}
</script>

<style scoped>

.main-container{
    margin-top: 5%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;


}

.project-card{
    margin: 10px;
    padding: 10px;
    flex-wrap:0 0 40%;
    background-color: #fff;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.project-card img{
        height: 10rem;
    }

.links{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
}

.links img{
height: 1.5rem;
margin: 5px;

}
</style>