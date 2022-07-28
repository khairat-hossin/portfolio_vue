<template>

    <Navbar />
    <div class="container">
        <Intro />
        <Skills />
    </div>
    
</template>

<script>
import Navbar from './components/Navbar.vue'
import Intro from './components/Intro.vue'
import Skills from './components/Skills.vue'
export default {
    name: "App",
    components:{
        Navbar,
        Intro,
        Skills
    },
    data(){
        return {

        }
    }
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /* text-align: center; */
    color: #2c3e50;
   
}
body{
    background: #13203B;
}

</style>
