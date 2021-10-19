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
                        <p class="text-gray-700 text-base mb-4">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi unde consequatur, ab eum exercitationem laborum, explicabo optio quaerat molestiae eos dolor, cupiditate placeat delectus est.
                        </p>
                        <a href="" class="bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-4 rounded">Open</a>
                    </div>
                    <div class="px-6 py-4">
                        <span 
                            class="inline-block bg-gray-200 rounded-full px-3 py-1 my-1 text-sm font-semibold text-gray-700 mr-2"
                            >
                            #somehash
                            https://youtu.be/aaaFahk2dOw?t=1218
                        </span>
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