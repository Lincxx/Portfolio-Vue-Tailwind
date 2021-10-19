<template>
<div>
    <NavBar :ishome="false"/>
    <div class="pt-24 min-h-screen w-screen top flex flex-col flex-wrap justify-center items-center px-8 bg-gray-200 shadow-lg">
        <div class="w-full flex flex-wrap">
            <div class="w-1/4 p-2 mb-8" v-for="(project, index) in projects" :key="index">
               <Card :project="project"/> 
            </div>
            
        </div>
    </div>
</div>
    
</template>

<script>
    import NavBar from '../components/NavBar'
    import Card from '../components/Card'
    import projects from '../data/project'
    export default {
        name: 'Portfolio',
        components: {
            NavBar,
            Card
        },
        data() {
            return {
                projects: projects
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>