<template>
    <main>
        <section class="middle-section">
            <div>
                <h2>Lorem, ipsum dolor.</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio tempora nostrum voluptatibus obcaecati. A, harum.</p>
            </div>
            <div>
                <h2>Lorem, ipsum dolor.</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere quod natus itaque animi minima odio.</p>
            </div>
            <div>
                <h2>Lorem, ipsum dolor.</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos nostrum mollitia facilis officia quae harum.</p>
            </div>
        </section>
        <section>
            <h3>Ouvrir un compte</h3>
            <div>
                <h3>Entreprise</h3>
                <img src="" alt="">
            </div>
            <div>
                <h3>Client</h3>
                <img src="" alt="">
            </div>

        </section>
    </main>
</template>


<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent ({
    name : "HomeBody"
})
</script>


<style scoped>

main {
    margin-top: 100px;
}
.middle-section  {
    display: grid;
    grid-template-columns: repeat(3,1fr);
}

.middle-section div h2  {
    margin-bottom: 20px;
}


</style>