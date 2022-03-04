<template>
    <div class="container">
        <div class="row">
            <div class="logo">
              <img src="../assets/avada-img/logo.png" alt="logo Avada">
            </div>
            <div class="nav">
                <nav>
                    <ul>
                        <li v-for="(link, index) in links" :key="index">
                            <a href="#">{{link.text}}</a>
                        </li>
                        <!--
                        <li>Service</li>
                        <li>About</li>
                        <li>Videos</li>
                        <li>Blog</li>
                        <li>Store</li>
                        -->
                        <button class="btn-b">schedule a workout</button>
                    </ul>
                </nav>
            </div>
        </div>
        <div id="jumbotron">
            <div class="row-1">
                <div class="side-l">
                    <span>Certified fitness professional</span>
                    <h1>Take control of your health</h1>
                    <p> quae earum quia placeat omnis fugit accusantium dignissimos fuga.</p>
                    <button class="btn-b">Visit my YouTube channel</button>
                    <button>Buy Avada today</button>
                </div>
            </div>
            
        </div>
        <section id="B-color">
            <div class="row-1">
                <div class="slide">
                    <img src="../assets/avada-img/service6-2x.jpg" alt="">
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/box1-2x.jpg" alt="">
                </div>
                <div class="slide">
                    <img src="../assets/avada-img/box3-2x.jpg" alt="">
                </div>
            </div>
            <div class="row-1">
                <div class="text-center">
                    <p>"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</p>
                    <span>Brad Johnson</span>
                    <span>Las Vegas</span>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name:"MyHeader",
    data() {
        return {
            links: [
                {
                    text: 'Home',
                    url:'#',
                },
                {
                    text: 'Service',
                    url:'#',
                },
                {
                    text: 'About',
                    url:'#',
                },
                {
                    text: 'Videos',
                    url:'#',
                },
                {
                    text: 'Blog',
                    url:'#',
                },
                {
                    text: 'Store',
                    url:'#',
                },
            ],
        }
    }

}
</script>

<style lang="scss">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.row-1 {
    width: 80%;
    margin: 0px auto;
    border: solid 1px wheat;
}
.container {
    width: 100%;
    min-height: 80px;
    background-color:black;
    .row {
        width: 80%;
        height: 80px;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .nav li {
            display: inline-block;
            margin:0px 7px;
            color: #71888c;
            a {
                text-decoration: none;
                color: lightgrey;
            }
            
        }
        .btn-b {
            background: #4154ff;
            color: azure;
            width: 150px;
            height: 40px;
            border-radius: 50px;
            border: solid 1px #4154ff;
            margin: 0px 5px;
            cursor: pointer;
        }
    }
    #jumbotron {
        min-height: 450px;
        background-image: url("../assets/avada-img/slider82x-scaled.jpg");
        background-size:cover;
        display: flex;
        align-items: center;
        .side-l {
            width: 60%;
            span {
                color: red;
                font-size: 20px;
                margin: 10px 0px;
            }
            h1 {
                color: white;
                font-size: 50px;
                margin: 10px 0px;
            }
            p {
                color: #8d9192;
                margin: 20px 0px;
                font-size: 20px;
            }
            .btn-b {
            background: #4154ff;
            color: azure;
            width: 200px;
            height: 40px;
            border-radius: 50px;
            border: solid 1px #4154ff;
            margin: 0px 5px;
            cursor: pointer;
            }
            button {
                color:white;
                background-color: transparent;
                width: 150px;
                height: 40px;
                border-radius: 50px;
                border: solid 1px lightgrey;
                margin: 0px 5px;
                cursor: pointer;

            }
            
        }
    }
    #B-color {
        min-height: 400px;
        background: linear-gradient(135deg, rgb(9, 9, 133) 10%, rgb(141, 4, 4));
        .row-1 {
            display: flex;
            justify-content: space-between;
        }
        .slide {
            margin-top: -50px;
            img {
                max-width: 300px;
                border-radius: 0px 0px 30px 0px;
            }
        }
        .text-center {
            width: 80%;
            margin: 0px auto;
            margin-top: 100px;
            color: white;
            font-size: 52px;
            text-align: center;
            span {
                font-size: 20px;
                margin-right: 10px;
            }
        }


    }
}


</style>