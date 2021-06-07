<template>
    <div class="container-navbar">
        <div class="topnav" id="myTopnav">
            <a href="#" class="active">News</a>
            <a class="navbar-right" href="/">Link 1</a>
            <a href="/detail">Link 2</a>
            <a @click="myFunction()" id="icon" class="icon">&#9776;</a>
            <a @click="buttonClose()" id="close" class="close">&times;</a>
        </div>
    </div>
</template>

<script>
export default {
    methods: {
         myFunction() {
            if (myTopnav.className === "topnav") {
                myTopnav.className += " responsive";
            } else {
                myTopnav.className = "topnav";
            }

            if(myTopnav.className += " responsive") {
                document.getElementById("close").style.display = "block"
                document.getElementById("icon").style.display = "none"
            }
        },

        buttonClose() {
            if(myTopnav.className === "topnav") {
                myTopnav.className -= "responsive"
            } else {
                myTopnav.className = "topnav"
            }
            if ( myTopnav.className != "responsive" ) {
                document.getElementById("close").style.display = "none"
                document.getElementById("icon").style.display = "block"
            }
        }
    }

}
</script>

<style>
.navbar-right {
    margin-left: 800px;
}
.topnav {
    overflow: hidden;
    background-color: #86d0c1;
}

.topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
}

.topnav a:hover {
    color: rgb(255, 255, 255, 0.5);
}

.topnav a.active {
    color: white;
    margin-left: 50px;
}
  
.topnav .icon {
    display: none;
}
.topnav .close {
    display: none;
}
  
@media screen and (max-width: 600px) {
    .topnav a:not(:first-child) {
        display: none;
    }
    .topnav a.icon {
      float: right;
      display: block;
    }
    
    .navbar-right {
        margin: 0;
    }
    .topnav a.active {
        margin: 0;
    }

}
  
@media screen and (max-width: 600px) {
    .topnav, .responsive {
        position: relative;
    }
    .topnav.responsive .icon {
        position: absolute;
        right: 0;
        top: 0;
    }
    .topnav .close {
        position: absolute;
        right: 0;
        top: 0;
    }
    .topnav.responsive a {
        float: none;
        display: block;
        text-align: left;
    }
    .close {
        display: none;
    }
}
</style>