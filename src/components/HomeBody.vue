<template>
    <main>
        <section class="middle-section">
            <div>
                <h2>Lorem, ipsum dolor.</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio tempora nostrum voluptatibus
                    obcaecati. A, harum.</p>
            </div>
            <div>
                <h2>Lorem, ipsum dolor.</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere quod natus itaque animi minima odio.</p>
            </div>
            <div>
                <h2>Lorem, ipsum dolor.</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos nostrum mollitia facilis officia quae harum.
                </p>
            </div>
        </section>
        <section class="bottom-section">
            <h3>Ouvrir un compte</h3>
            <div class="different-account">
                <div>
                    <h3>Entreprise</h3>
                    <img src="@/assets/images/entrepreneur.png" alt="">
                </div>
                <div>
                    <h3>Client</h3>
                    <img src="@/assets/images/client-b2c.png" alt="">
                </div>
            </div>

        </section>
    </main>
</template>


<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
    name: "HomeBody"
})
</script>


<style scoped>
main {
    margin-top: 100px;
}

.middle-section {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    column-gap: 10px;
    margin-bottom: 30px;
}

.middle-section div h2 {
    margin-bottom: 20px;
}
.different-account {
    display: grid;
    grid-template-columns: repeat(2,1fr);
}

.different-account h3 {
    text-align: center;
}

.bottom-section  {
    margin-top: 20px;
}

.bottom-section h3 {
    margin-top: 10px;
    margin-bottom: 10px;
}
</style>