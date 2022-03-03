<template>
    <div class="pages">
        <welcomeSection/>
        <loginForm />
    </div>
</template>
<style scoped>
.pages{
    display: flex;
    flex-direction: row;
    width:100vw;
    height: 100vh;
}
.welcomeSection{
    border: 2px solid green;
    width: 50vw;
    height: 100vh;
}
</style>
<script>
import welcomeSection from './components/LandingPage/welcomeSection.vue'
import loginForm from './components/loginpage/loginForm.vue'

export default {
    name:'LoginVeiw',
    components: {
        welcomeSection,
        loginForm
    }
}
</script>
