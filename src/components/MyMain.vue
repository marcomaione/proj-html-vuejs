<template>
    <div>
        <section>
            <div class="row-2">
                <div class="left">
                    <img src="../assets/avada-img/service15-2x.jpg" alt="">
                    <div class="left-play">
                        <i class="fa-solid fa-circle-play"></i>
                    </div>
                </div>
                <div class="right">
                    <a href="#">Tune up your workouts</a>
                    <h2>The best health & fitness advice online</h2>
                    <img src="../assets/avada-img/unnamed.jpg" alt="">
                    <i class="fa-brands fa-youtube"></i>
                    <span>You Tube</span>
                    <span>999+</span>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe eum quae ipsam velit Animi eos provident totam non molestias.</p>
                    <button>Visit my You Tube chanel</button>
                </div>
            </div>
        </section>
        <section>
            <div class="row-3">
                <span>Featured playlists</span>
                <a href="#">View all Videos > </a>
            </div>
            <div class="row-3">
                <div class="slide">
                    <img src="../assets/avada-img/video2-2x.jpg" alt="">
                    <div class="play">
                        <i class="fa-solid fa-circle-play"></i>
                    </div>
                    <p>Thighs & glute workout</p>
                    <span>Increase your mobility</span>
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/video7-2x.jpg" alt="">
                    <div class="play">
                        <i class="fa-solid fa-circle-play"></i>
                    </div>
                    <p>Lift, firm & perk up</p>
                    <span>Feel young again</span>
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/video9-2x.jpg" alt="">
                    <div class="play">
                        <i class="fa-solid fa-circle-play"></i>
                    </div>
                    <p>Slim & trim your waist</p>
                    <span>Shed those extra pounds</span>
                </div>
            </div>
        </section>
        <section>
            <div class="offers">
                <div class="row-3">
                    <div class="subscribe">
                        <span>Join our mailing list today</span>
                        <h1>Insider offers & flash sales in your inbox every week.</h1>
                        <input type="text">
                        <button>Subscribe</button>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam asperiores quo quaerat. Voluptas placeat molestias labore non aut nisi.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="black">
            <div class="row-3">
                <div class="item">
                    <h4>Team training</h4>
                    <span>Find a partner</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum obcaecati ipsam est ut temporibus necessitatibus sint cumque non doloribus. Placeat accusantium quo rem assumenda, nostrum quibusdam corrupti beatae aspernatur nemo!</p>
                    <a href="#">Find a partner > </a>
                </div>
                <div class="item">
                    <i class="fa-solid fa-dumbbell"></i>
                    <h4>Crossfit workout</h4>
                    <span>Push your limits</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum obcaecati ipsam est ut temporibus necessitatibus sint cumque non doloribus. Placeat accusantium quo rem assumenda, nostrum quibusdam corrupti beatae aspernatur nemo!</p>
                    <a href="#">Find a partner > </a>
                </div>
                <div class="item">
                    <i class="fa-solid fa-weight-scale"></i>
                    <h4>Weigth loss</h4>
                    <span>Shed those pounds</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum obcaecati ipsam est ut temporibus necessitatibus sint cumque non doloribus. Placeat accusantium quo rem assumenda, nostrum quibusdam corrupti beatae aspernatur nemo!</p>
                    <a href="#">Find a partner > </a>
                </div>
            </div>
        </section>
        <section>
            <div class="row-3">
                <span>Latest articles</span>
                <a href="#">Read all articles > </a>
            </div>
            <div class="row-3">
                <div class="slide">
                    <img src="../assets/avada-img/blog4-2x-400x258.jpg" alt="">
                    <p>The best protein shake</p>
                    <span id="c">By admin | November 26th,2019 | Gym</span>
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/blog1-2x-400x258.jpg" alt="">
                    <p>Ultimate cardio workout</p>

                    <span id="c">By admin | November 26th,2019 | Gym</span>
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/blog3-2x-400x258.jpg" alt="">
                    <p>New juices available now</p>
                    <span id="c">By admin | November 26th,2019 | Gym</span>
                </div>
            </div>
        </section>
        <section>
            <div class="jumbotron">
                <div class="row-2">
                    <div class="text">
                        <h2>" I've failed over and over again in my life.And thet is why I succeed."</h2>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nostrum, dolor quos cumque excepturi doloremque impedit eius sequi, qui iure autem suscipit itaque accusantium odio ut ratione officiis voluptates aut minus</p>
                        <button>Buy Avada today ></button>
                    </div>
                </div>

            </div>
        </section>
    </div>
</template>

<script>
export default {
    name:"MyMain"

}
</script>

<style lang="scss">

.fa-solid {
    color: white;
    font-size: 20px;
    margin-top: 5px;
}
.black {
    min-height: 500px;
    margin-top: -30px;
    background-color: black;
}

section {
    width: 100%;
}
#c {
    color: rgb(34, 34, 34);
}
.row-2 {
    display: flex;
    .left {
    width: 50%;
    margin-top: -50px;
    position: relative;
    .left-play {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
        position: absolute;
        bottom: 0;
        right: 0;
        top: 0;
        left: 0;
        .fa-circle-play {
            font-size: 60px;
            border:solid 2px black;
            border-radius: 50%;
        }
    }
    }
    img {
        max-width:100%;
        border-radius: 0px 0px 30px 0px;
    }
    .right {
        width: 50%;
        margin-top: 150px;
        margin-left: 100px;
        img {
            margin-top: 10px;
        }
        a {
            text-decoration: none;
            color: blue;
            font-size: 25px;
        }
        h2 {
            font-size: 50px;
            margin: 25px 0px;
        }
        span {
            color: black;
            margin:40px 5px;
            vertical-align: middle;
        }
        p {
            margin-top: 20px;
            color: rgb(124, 124, 124);
        }
        button {
            background: red;
            color: azure;
            width: 200px;
            height: 40px;
            border-radius: 50px;
            border: solid 1px red;
            margin: 25px 0px;
            cursor: pointer;
        }
    
    }

}
.row-3 {
    width: 70%;
    margin: 30px auto;
    display: flex;
    justify-content: space-between;
    span {
        font-size: 20px;
    }
    a {
        text-decoration: none;
        color: black;
    }
    .slide {
        width: 30%;
        text-align: center;
        position: relative;
        .play {
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            height: 100%;
            position: absolute;
            bottom: 0;
            right: 0;
            top: 0;
            left: 0;
            .fa-circle-play {
                font-size: 50px;
                margin-bottom: 80px;
            }
        }
        img {
            width:100%;
            height: 200px;
            border-radius: 0px 0px 30px 0px;
        }
        p {
            font-size: 20px;
            margin: 10px 0px;
        }
        span {
            color: blue;
            font-size: 15px;
        }
    }
}
.offers {
    min-height: 450px;
    background: linear-gradient(90deg, rgb(0,0,0) 40%, rgba(0,0,0,0)),url("../assets/avada-img/banner1-2x.jpg");
    background-size: cover;
    .subscribe {
        margin: 100px 0px;
        width: 70%;
        span {
            color: red;
            font-size: 20px;
        }
        h1 {
            margin-top: 25px;
            color: white;
            font-size: 40px;
        }
        input {
            margin-top: 25px;
            border-radius: 50px;
            width: 350px;
            height: 40px;
            border: solid 1px white;
        }
        button {
            background:#4154ff;
            color: azure;
            width: 200px;
            height: 40px;
            border-radius: 50px;
            border: solid 1px #4154ff;
            margin: 25px 20px;
            cursor: pointer;
        }
        p {
            margin-top: 20px;
            color: rgb(124, 124, 124);
        }
    }
}
.item {
    margin-top: 80px;
    text-align: center;
    width: 30%;
    height: 300px;
    border: solid 4px blue;
    border-radius: 10px;
    h4 {
        color:white;
        margin: 15px 0px;
    }
    span {
        color:yellow;
    }
    p {
        margin:20px 0px;
        color: rgb(124, 124, 124); ;
    }
    a {
        text-decoration: none;
        color: white;
    }
}
.jumbotron {
    min-height: 450px;
    background-image: url("../assets/avada-img/banner2-2x.jpg");
    background-size: cover;
    .row-2 {
        display: flex;
        justify-content: center;
        .text {
            margin-top: 150px;
            width: 70%;
            text-align: center;
            h2 {
                font-size: 40px;
                color: white;
            }
            p {
                color: white;
                margin: 30px 0px;
            }
            button {
            background:#4154ff;
            color: azure;
            width: 150px;
            height: 40px;
            border-radius: 50px;
            border: solid 1px #4154ff;
            margin: 25px 20px;
            cursor: pointer;
        }
        }
    }
}



</style>
install @fortawesome/fontawesome-free

