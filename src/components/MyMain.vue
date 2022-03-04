<template>
    <div>
        <section>
            <div class="row">
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

    </div>
</template>

<script>
export default {
    name:"MyMain"

}
</script>

<style lang="scss">
.row {
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


</style>