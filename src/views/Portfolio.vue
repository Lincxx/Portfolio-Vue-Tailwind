<template>
<div>
    <NavBar :ishome="false"/>
    <div class="pt-24 min-h-screen w-screen top flex flex-col flex-wrap justify-center items-center px-8 bg-gray-200">
        <div class="w-full flex flex-wrap">
            <div class="w-1/4 p-2">
                <div class="bg-white rounded shadow-xl">
                    <img src="" alt="">
                    <div class="px-6 py-4">
                        <p class="font-bold text-gray-900 text-lg mb-2">Project Name</p>
                    </div>
                </div>
            </div>
        </div>
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