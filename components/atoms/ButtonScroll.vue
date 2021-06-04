<template>
    <div>
        <button @click="topFunction()" id="myBtn" title="Go to top">Back To Top</button>
    </div>
</template>

<script>
    window.onscroll = function() {
        if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 1000) {

                document.getElementById("myBtn").style.display = "block";

        } else {

            document.getElementById("myBtn").style.display = "none";

        }
    }
export default {
    methods: {
        
        // scrollFunction() {

        //     if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 1000) {

        //         document.getElementById("myBtn").style.display = "block";

        //     } else {

        //         document.getElementById("myBtn").style.display = "none";

        //     }

        // },
        topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
    }

}
</script>

<style>
#myBtn {
 
  display: none;
 
  position: fixed;
 
  bottom: 20px;
 
  right: 30px;
 
  z-index: 99;
 
  border: none; 
 
  outline: none;
 
  background-color: #86d0c1;
 
  color: white;
 
  cursor: pointer;
 
  padding: 15px;
 
  border-radius: 10px;
 
}
 
 
#myBtn:hover {
 
  background-color: #2c3e50;
 
}
</style>