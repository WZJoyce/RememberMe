<template>
    <div>
        <the-header title="RememberMe"></the-header>
        <the-resources></the-resources>
    </div>
    
    
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';
export default {
    components:{
        TheResources,
        TheHeader,
    },
    data() {
        return{
           /*  storedResources:[
                {
                    id: 'official-guide', 
                    title: 'Official Guide', 
                    description: 'The offical Vue.js documentation',
                    link: 'https://vuejs.org',
                },
                {
                    id: 'google', 
                    title: 'Google', 
                    description: 'Learn to google...',
                    link: 'https://google.org',
                }
            ] */
        }

    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
* {
    box-sizing: border-box;
}

html {
    font-family: 'Roboto', sans-serif;
}

body {
    margin: 0;
}
</style>
