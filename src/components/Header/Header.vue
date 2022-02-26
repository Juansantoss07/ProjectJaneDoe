<script>

    export default{
        name:"Header",

        methods:{
            menu(){
                document.getElementById('nav').style.display = 'flex';
                document.getElementById('btn-mobile').style.display = 'none';
            },
            
            close(){
                document.getElementById('nav').style.display = 'none';
                document.getElementById('btn-mobile').style.position = 'fixed';
                document.getElementById('btn-mobile').style.display = 'block';
            }
        }
    }


</script>

<template>
<div class="box-nav">
     <div class="content-header">
        <button @click="menu" class="menu-btn" id="btn-mobile">
            <i class="bi bi-list"></i>
        </button>
        <nav class="sidebar" id="nav">
             <button @click="close" class="menu-btn-close" id="btn-mobile">
            <i class="bi bi-list"></i>
        </button>
            <div class="links">
                <ul>
                    <li>
                        <a href="#">Home</a>
                        <a href="#">Portfolio</a>
                        <a href="#">About</a>
                        <a href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</div>
   
</template>

<style lang="scss" src="./style.scss" scoped/>