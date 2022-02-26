<script>
    export default{
        name:"Home"
    }
</script>

<template>
    <div id="home">
        <h1>Jane Doe</h1>
        <p>Photographer and Web Designer.</p>
        <button>
            <i class="bi bi-download"></i> Download Resume
        </button>
    </div>
</template>

<style lang="scss" scoped>
    div{
        padding:9rem 0;
        display: flex;
        flex-direction: column;
        align-items:center;
        justify-content: center;
        width: 100%;

        h1{
            color: #000;
            font-size: 64px;
            font-weight: 500;
        }

        p{
            color:#000;
            font-size: 15px;
            margin: 2rem 0;
        }
    }

    @media(max-width:600px){
        h1{
            text-align: center;
        }
    }
</style>