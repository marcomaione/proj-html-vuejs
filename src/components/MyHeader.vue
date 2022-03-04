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
                        <button>schedule a workout</button>
                    </ul>
                </nav>
            </div>
        </div>
        <div id="jumbotron">
            <div>
                
            </div>
            
        </div>
        <section id="B-color"></section>
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
        button {
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
        background-size:cover ;
    }
    #B-color {
        min-height: 400px;
        background: linear-gradient(135deg, rgb(9, 9, 133) 10%, rgb(141, 4, 4));

    }
}


</style>