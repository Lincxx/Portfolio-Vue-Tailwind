<template>
<div>
    <NavBar :ishome="false"/>
    <div class="pt-24">
        hello
    </div>
</div>
    
</template>

<script>
    import NavBar from '../components/NavBar'
    export default {
        components: {
            NavBar,
        },
       name: 'Portfolio' 
    }
</script>

<style lang="scss" scoped>

</style>