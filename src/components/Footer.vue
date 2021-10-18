<template>
    <div class="flex justify-center items-center">
        <div class="h-20 bottom-0 py-8 flex">
            <p class="pr-2">&copy; Jeremy Lincoln</p>
            <a class="github" href="" target="_blank">
                <Github />
            </a>
            <a class="facebook" href="" target="_blank">
                <Facebook />
            </a> 
            <a class="twitter" href="" target="_blank">
                <Twitter />
            </a>
            
        </div>
    </div>
</template>

<script>
import Github from 'vue-material-design-icons/Github';
import Facebook from 'vue-material-design-icons/Facebook';
import Twitter from 'vue-material-design-icons/Twitter';


    export default {
      name: 'Footer' ,
      components: {
          Github, 
          Facebook,
          Twitter
      } 
    }
</script>

<style lang="scss" scoped>
.github:hover{
    @apply text-red-700;
}
.facebook:hover{
    @apply text-blue-700;
}
.twitter:hover{
    @apply text-blue-400;
}
</style>