<template>
    <main class="outer-rectangle">
        <!-- Left Column -->
        <div class="left-col-card">
            <!-- Left Column Text-->
            <div>
                <h3>Lorem ipsum dolor sit amet.</h3>
                <h4>Lorem, ipsum dolor.</h4>
            </div>
            <!-- Left columns buttons-->
            <div class="bottom-buttons">
                <a class="btn btn-full">Get Started</a>
                <a class="btn btn-outline">Go explore</a>
            </div>
        </div>
        <!-- Right colums buttons-->
        <div class="image-div">
            <img src="@/assets/images/reno-construction-home.png" >
        </div>
        
    </main>
</template>


<script lang="ts">
import  { defineComponent } from "vue"

export default defineComponent({
    name : "HomeViewCard"
});

</script>


<style scoped>

    .outer-rectangle {
        display: grid;
        grid-template-columns: 55% 45%;
        background-color : #FFF8E8;
        height: fit-content;
        padding: 10px 0px 0px 20px;
        border-radius: 2%;
        box-shadow: 5px 5px 15px 5px rgba(0,0,0,0);
        overflow: clip;
    }

    .left-col-card {
        display: grid;
        grid-template-rows: 1fr 1fr;
        padding-bottom : 20px;
    }

    .left-col-card .bottom-buttons {
        display: flex;
        align-items: flex-end ;
    }

    .btn {
        border : 1px solid #A7725D;
        padding : 10px 45px;
        border-radius: 5%;
    
    }
    .btn-full {
        background-color : #A7725D;
        color : white;
    }
    .btn-full:hover {
       transform: scale(.98);
       background-color : #df9a7e;
    }
    .btn-outline {
        color : #A7725D;
    }
    .btn-outline:hover {
        transform: scale(.98);
        background-color : #df9a7e;
        color:white
    }
    
    .image-div {
       position: relative;
    }

    img {
        position: relative;
        left : 50px;
    }

    

</style>