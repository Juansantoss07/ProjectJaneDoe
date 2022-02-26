<script>
    export default{
        name:"Contact"
    }
</script>

<template>
    <div class="content-contact">
        <div class="title">
            <h1>Contact Me</h1>
        </div>
        <hr>
        <div class="container-contact">
            <div class="info">
                <i class="bi bi-geo-alt-fill"></i>
                <p>
                    Chicago, US
                </p>
            </div>
            <div class="info">
                <i class="bi bi-telephone-fill"></i>
                <p>
                    Phone: +00 151515
                </p>
            </div>
            <div class="info">
                <i class="bi bi-envelope-fill"></i>
                <p>
                    Email: mail@mail.com
                </p>
            </div>
        </div>
        <div class="contact-img">
            <img src="/public/img/map.jpg" alt="">
        </div>

        <div class="form">
            <div class="title-form">
                <p>
                    Lets get in touch. Send me a message:
                </p>
            </div>

            <div class="form-inputs">
                <form action="/">
                    <input type="text" placeholder="Name">
                    <input type="email" placeholder="Email">
                    <input type="text" placeholder="Subject">
                    <input type="text" placeholder="Message">
                    <button  class="btn-sub" type="submit">
                       <i class="bi bi-send-fill"></i> Send Message
                    </button>
                </form>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

    hr{
        margin: 0 2rem;
        border-color: #dfdede;
        opacity: .4;
        border-style: solid;
    }
    .container-contact{
        padding: 1rem 2rem;

        .info{
            display: flex;
            align-items: center;
            padding: 1rem 1rem 0 1rem;
        }

        .bi{
            font-size: 2rem;
            color: #7a7a7a;
            padding-right: 1rem;
        }

        p{
            color: #7a7a7a;
        }
    }

    .contact-img{
            display: flex;
            width: 100%;
            padding: 1rem 2rem;
        }

        .contact-img img{
            width: 100%;
            height: 100%;
            padding: 1rem;
            filter: grayscale(75%);
        }

        .form{
            display: flex;
            flex-direction: column;
            padding: 1rem 2rem;

            .title-form{
                padding: 1rem;
                color: #757575;
            }

            .form-inputs{
                display: flex;
                width: 100%;

                form{
                    padding: 1rem;
                    width: 100%;
                    height: 100%;
                    display: flex;
                    flex-direction: column;
                    justify-content: space-around;

                    input{
                        padding: 1.5rem 0.5rem;
                        margin-bottom: 1rem;
                    }

                    .btn-sub{
                        width: 30%;

                        .bi{
                            padding-right: 1rem;
                        }
                    }
                }
            }
        }
</style>