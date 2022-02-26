<script>
    export default{
        name: "MyPrice"
    }
</script>

<template>
    <div class="content-myprice">
        <div class="title">
            <h1>My Price</h1>
        </div>
        <div class="container-price">
            <div class="table">
                <div class="title-table">
                    <h3>Basic</h3>
                </div>
                <div class="table-prof">
                    <p>Web Design</p>
                </div>
                 <div class="table-prof">
                     <p>Photography</p>   
                </div>
                 <div class="table-prof">
                        <p>5GB Storage</p>
                </div>
                 <div class="table-prof">
                        <p>Mail Support</p>
                </div>
                <div class="table-price">
                    <h2>$10</h2>
                    <p>per month</p>
                </div>
                <div class="table-btn">
                    <button class="btn-tb">
                        Sign Up
                    </button>
                </div>
            </div>

                        <div class="table">
                <div class="title-table-pro">
                    <h3>Pro</h3>
                </div>
                <div class="table-prof">
                    <p>Web Design</p>
                </div>
                 <div class="table-prof">
                     <p>Photography</p>   
                </div>
                 <div class="table-prof">
                        <p>50GB Storage</p>
                </div>
                 <div class="table-prof">
                        <p>Mail Support</p>
                </div>
                <div class="table-price">
                    <h2>$25</h2>
                    <p>per month</p>
                </div>
                <div class="table-btn">
                    <button class="btn-tb">
                        Sign Up
                    </button>
                </div>
            </div>
            
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .content-myprice{
        display: flex;
        flex-direction: column;
        width: 100%;

        .container-price{
            display: flex;
            flex-direction: row;
            width: 100%;
            justify-content: space-evenly;
            padding: 1rem 2rem;

            .table{
                display:flex;
                flex-direction: column;
                width: 48%;
                border: 1px solid #cfcfcf;

                .title-table{
                    background: #616161;
                    display: flex;
                    padding: 2rem 1rem;
                    color: #fff;
                    justify-content: center;
                    align-items: center;
                    font-size: 1.2rem;
                }

                .title-table-pro{
                    background: #000;
                    display: flex;
                    padding: 2rem 1rem;
                    color: #fff;
                    justify-content: center;
                    align-items: center;
                    font-size: 1.2rem;
                }

                .table-prof{
                    background-color: transparent;
                    color: #757575;
                    padding: 1rem;
                    border-bottom: 1px solid #cfcfcf;
                    display:flex;
                    justify-content: center;
                }

                .table-price{
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: center;
                    width: 100%;
                    padding:1rem;
                    border-bottom: 1px solid #cfcfcf;
                }

                .table-btn{
                    width:100%;
                    display: flex;
                    justify-content: center;
                    padding: 1rem;
                    background-color: #f1f1f1;
                }

                .btn-tb{
                    background-color: #fff;
                    color: #000;
                }

                .btn-tb:hover{
                    background-color: #000;
                    color: #fff;
                }
            }

            .table:hover{
                box-shadow: 7px 7px 7px #cfcfcf;
            }
        }

    }
</style>