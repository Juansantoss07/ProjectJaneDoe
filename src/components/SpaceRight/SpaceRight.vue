<script>
    import Home from "../Sections/Home.vue"
    import MyPortfolio from "../Sections/MyPortfolio.vue"
    import About from "../Sections/About.vue"
    import MySkiils from "../Sections/MySkiils.vue"
    import MyReputation from "../Sections/MyReputation.vue"
    import MyPrice from "../Sections/MyPrice.vue"
    import Contact from "../Sections/Contact.vue"
    import Footer from "../Footer/Footer.vue"

    export default{
        name:"SpaceRight",
        components:{
    Home,
    MyPortfolio,
    About,
    MySkiils,
    MyReputation,
    MyPrice,
    Contact,
    Footer
}
    }
</script>

<template>
<div class="sections">
     <Home/>
    <MyPortfolio/>
    <About/>
    <MySkiils/>
    <MyReputation/>
    <MyPrice/>
    <Contact/>
    <Footer/>
</div>
</template>

<style src="./style.scss" lang="scsss" />