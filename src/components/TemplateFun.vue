<template>
    <div>
        <h3>{{blog_title}}</h3>
        <p>{{blog_content}}</p>
        <img :src="blog_image_url"/>

    </div>
</template>

<script>
    export default {
        data() {
            return {
                blog_content: "Do not bother of what others are saying about you, own your world",
                blog_title: "Story of my life",
                blog_image_url: 'https://unsplash.com/s/photos/life',

                
            }
        },
        
    }
</script>
<style>
</style>