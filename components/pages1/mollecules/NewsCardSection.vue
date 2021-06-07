<template>
    <div id="testimoni" class="container-testimoni">
        <div class="testimoni-content">
            <div class="testimoni-left">
                <img 
                    class="testimoni-image"
                    src="~/assets/image/man.png" 
                    alt="image not found"
                >
                <p class="testimoni-left-paragraf">Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero molestiae recusandae doloribus, laudantium totam optio veritatis ab? Tempora, ullam voluptate autem quos eaque aut nobis quam. Nobis commodi velit consectetur.</p>
            </div>
            <div class="testimoni-middle">
                <img 
                    class="testimoni-image"
                    src="~/assets/image/boy.png" 
                    alt="image not found"
                >
                <p class="testimoni-middle-paragraf">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, sequi possimus, sunt cupiditate enim provident autem dolores fuga iusto cum itaque tempore, voluptas voluptates repellendus error temporibus voluptatem rerum laboriosam!</p>
            </div>
            <div class="testimoni-right">
                <img 
                    class="testimoni-image"
                    src="~/assets/image/girl.png" 
                    alt="image not found"
                >
                <p class="testimoni-right-paragraf">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est quibusdam officia non illum at! Facere maiores rem explicabo, accusamus atque suscipit earum animi voluptatum sunt autem cum consequuntur dolore itaque.</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.container-testimoni {
    padding-top: 50px;
}
.testimoni-content {
    display: flex;
    width: 90%;
    margin-left: 5%;
    justify-content: space-between;
    margin-top: 60px;
    text-align: center;
}
.testimoni-left, 
.testimoni-middle,
.testimoni-right {
    width: 500px;
    height: auto;
    display: block;
    border-radius: 40px;
    padding: 20px;
    box-shadow: inset 0px 0px 3px rgb(0, 0, 0, 0.25);
}
.testimoni-image {
    width: 124px!important;
    height: 124px;
    margin-top: 30px;
    border-radius: 50%;
    border:2px dashed #86d0c1;
    padding: 10px;
}
.testimoni-left-paragraf,
.testimoni-middle-paragraf,
.testimoni-right-paragraf {
    font-size: 22px;
    margin-top: 50px;
    width: 90%;
    margin-left: 5%;
}
@media (max-width: 800px) {
    .testimoni-content {
        display: block;
        /* padding: 50px; */
        width: 90%!important;
        margin: 0;
        margin-left: 5%;
        text-align: center;
    }
    .testimoni-left, 
    .testimoni-middle,
    .testimoni-right {
        width: 100%;
        margin-top: 20px;
        border-radius: 10px;
    }
}
@media (max-width: 400px) {
    .testimoni-left, 
    .testimoni-middle,
    .testimoni-right {
        height: auto!important;
        width: 90%;
        margin-top: 20px;
        margin-left: 5%;
        display: block;
        text-align: center;
    }
    .testimoni-left-paragraf,
    .testimoni-middle-paragraf,
    .testimoni-right-paragraf {
        margin: 0;
        margin-left: 5%;
        margin-top: 30px;
    }
        
}

</style>