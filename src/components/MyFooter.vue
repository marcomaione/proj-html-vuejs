<template>
    <section>
            <div class="row-3">
                <div class="sponsor">
                    <img src="../assets/avada-img/sponsor-1-2x-200x103.png" alt="">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit quibusdam.</p>
                    <a href="#">Visit Yoga Studio ></a>
                </div>
                <div class="sponsor">
                    <img src="../assets/avada-img/sponsor-2-2x-200x103.png" alt="">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit quibusdam.</p>
                    <a href="#">Join Fitness Center ></a>
                </div>
                <div class="sponsor">
                    <img src="../assets/avada-img/sponsor-3-2x.png" alt="">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit quibusdam.</p>
                    <a href="#">Learn about FC ></a>
                </div>
                <div class="sponsor">
                    <img src="../assets/avada-img/sponsor-4-2x-200x103.png" alt="">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit quibusdam.</p>
                    <a href="#">Visit Power Gym ></a>
                </div>
            </div>
            <section>
                <div class="fo-jumbo">
                    <div class="crossfit">
                        <h2>Crossfit workout of the day</h2>
                        <p>November 15th,2019</p>
                        <a href="#">View all videos</a>
                    </div>
                </div>
            </section>
             <section class="black">
            <div class="row-3">
                <div class="info">
                    <img src="../assets/avada-img/logo.png" alt="">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum obcaecati ipsam est ut temporibus.</p>
                    <ul class="social">
                        <li><i class="fa-brands fa-facebook-f"></i></li>
                        <li><i class="fa-brands fa-twitter"></i></li>
                        <li><i class="fa-brands fa-youtube"></i></li>
                        <li><i class="fa-brands fa-instagram"></i></li>
                        <li><i class="fa-brands fa-linkedin-in"></i></li>
                    </ul>
                </div>
                <div class="info">
                    <h4>RECENT POST</h4>
                    <ul>
                        <li>
                            <a href="#">>The best protein shake</a>
                        </li>
                        <li>
                            <a href="#">>Ultimate cardio workout</a>
                        </li>
                        <li>
                            <a href="#">>New juice available</a>
                        </li>
                        <li>
                            <a href="#">>Tips to find training partners</a>
                        </li>
                        <li>
                            <a href="#">>20 best healthy recipes</a>
                        </li>
                    </ul>
                </div>
                <div class="info">
                    <h4>CONTACT INFORMATIONS</h4>
                    <p>4746 Tipple Road Michigan 48449</p>
                    <p>Mobile: 1.800.000.0000</p>
                    <p>Email : info@your-company.com</p>
                </div>
            </div>
        </section>
    </section>
</template>

<script>
export default {
    name:"MyFooter"

}
</script>

<style lang="scss">
.fa-brands {
    vertical-align: middle;
    color:red;
    margin: 0px 10px;
    cursor: pointer;
    font-size: 20px;
}
.sponsor {
    margin-top: 50px;
    width: 20%;
    text-align: center;
    img {
        max-width: 150px;
        margin-bottom: 25px;
    }
    p {
        margin-bottom: 25px;
    }

}
.fo-jumbo {
    margin-top: 80px;
    min-height: 450px;
    background-image: url("../assets/avada-img/banner14-2x.jpg");
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    .crossfit {
        text-align: center;
        h2 {
            color: white;
            font-size: 40px;
            margin-top: 80px;
        }
        p {
            color: yellow;
            font-size: 25px;
            margin: 10px 0px;
        }
        a {
            text-decoration: none;
            color: white;
        }

    }
    
}
.info {
    width: 30%;
    text-align: center;
    margin-top:150px;
    p {
        color: white;
        margin: 20px 0px;
    }
    h4 {
        color: white;
        font-size: 20px;
    }
    ul {
        list-style-type: none;
        margin-top: 30px;
        li {
            margin: 10px 0px;
            a {
                color: white;
            }
        }

    }
    span {
        color: white;
        padding: 20px 0px;
    }
}
.social li{
    display: inline-block;
}


</style>
@import "~@fortawesome/fontawesome-free/css/all.css";