<template>
    <div class="container">
        <div class="row">
            <div class="logo">
              <img src="../assets/avada-img/logo.png" alt="logo Avada">
            </div>
            <div class="nav">
              <ul>
                <li>Home</li>
                <li>Service</li>
                <li>About</li>
                <li>Videos</li>
                <li>Blog</li>
                <li>Store</li>
                <button>schedule a workout</button>
              </ul>
            </div>
        </div>
        <div id="jumbotron">
            <div>
                
            </div>
            
        </div>
    </div>
</template>

<script>
export default {
    name:"MyHeader"

}
</script>

<style lang="scss">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
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
            
        }
        button {
            background: #4154ff;
            color: azure;
            width: 150px;
            height: 40px;
            border-radius: 50px;
            border: solid 1px #4154ff;
            margin: 0px 5px;
        }
    }
    #jumbotron {
        min-height: 700px;
        background-image: url("../assets/avada-img/slider82x-scaled.jpg");
        background-size:cover ;

    }
}


</style>