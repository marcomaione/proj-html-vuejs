<template>
    <div>
        <section>
            <div class="row-2">
                <div class="left">
                    <img src="../assets/avada-img/service15-2x.jpg" alt="">
                </div>
                <div class="right">
                    <a href="#">Tune up your workouts</a>
                    <h2>The best health & fitness advice online</h2>
                    <span>you tube</span>
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
                    <p>Things & glute workout</p>
                    <span>Increase your mobility</span>
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/video7-2x.jpg" alt="">
                    <p>Lift, firm & perk up</p>
                    <span>Feel young again</span>
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/video9-2x.jpg" alt="">
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
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam asperiores quo quaerat. Voluptas placeat molestias labore non aut nisi recusandae.</p>
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
section {
    width: 100%;
}
.row-2 {
    display: flex;
    .left {
    width: 50%;
    }
    img {
        max-width:100%;
        border-radius: 0px 0px 30px 0px;
        margin-top: -50px;
    }
    .right {
        width: 50%;
        margin-top: 150px;
        margin-left: 100px;
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
            background-color: red;
            color: white;
            border: solid 1px black;
            margin:40px 5px;
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
    background-image: url("../assets/avada-img/banner1-2x.jpg");
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



</style>