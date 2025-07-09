<script setup>
import Header from './Header.vue';
import Posts from './Posts.vue';
import SideBar from './SideBar.vue';

</script>



<template>
    <div class="main-container">
        <Header/>
        <SideBar/>
        <Posts/>
    </div>
</template>




<style scoped>
.main-container{
    display: grid;
    grid-template-columns: 250px 1fr;
    grid-template-rows: auto 1fr;
    grid-template-areas: 
    "header header"
    "sidebar main";
    height: 100vh;
}
</style>