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
        </section>
</template>

<script>
export default {
    name:"MyFooter"

}
</script>

<style lang="scss">
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
        border: solid 1px wheat;
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

</style>