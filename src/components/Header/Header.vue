<script>

    export default{
        name:"Header",

        methods:{
            menu(){
                document.getElementById('nav').style.display = 'flex';
            },
            
            close(){
                document.getElementById('nav').style.display = 'none';
            }
        }
    }


</script>

<template>
<div class="box-nav">
     <div class="content-header">
        <button @click="menu" class="menu-btn w3-animate-right" id="btn-mobile">
            <i class="bi bi-list"></i>
        </button>
        <nav class="sidebar w3-animate-right" id="nav">
             <button @click="close" class="menu-btn-close" id="btn-mobile">
            <i class="bi bi-list"></i>
        </button>
            <div class="links">
                <ul>
                    <li>
                        <a @click="close" href="#home">Home</a>
                        <a @click="close" href="#port">Portfolio</a>
                        <a @click="close" href="#about">About</a>
                        <a @click="close" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</div>
   
</template>

<style lang="scss" src="./style.scss" scoped/>