<template>
    <div>
        <div class="jumbotron-container">
            <img class="jumbotron-image" src="~/assets/image/image-intro.png" alt="">
        </div>

        <div class="container-topic">
            <h1 class="title-topic">Showcase your thought provoking topics and ideas</h1>
            <p class="paragraf-satu-topic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda aut aliquam veritatis animi fuga unde recusandae, esse quis blanditiis at. Qui vitae, laudantium sed esse optio provident recusandae nostrum ut!. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Libero dolore voluptates soluta rem eius cupiditate eligendi hic. Maxime, earum quidem, asperiores voluptatem ab doloremque aliquam placeat, quis hic ducimus iusto. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Delectus architecto placeat, totam labore tenetur natus praesentium expedita quam dolores optio animi sunt, alias est officiis? Quam ut eius labore optio!</p><br>

            <p class="paragaraf-dua-topic">Lorem ipsum dolor sit amet consectetur adipisicing elit. A dolorum, corrupti exercitationem repellat quo, veritatis nostrum rerum, laudantium dolore incidunt blanditiis voluptatem! Numquam laudantium amet aliquid suscipit incidunt provident praesentium. Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda magni quam ducimus, aut error, neque consequuntur nesciunt cupiditate fugiat tempora labore nulla vitae necessitatibus repellat quia dolorem provident pariatur autem. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dicta repellat beatae, eveniet consequuntur eos pariatur recusandae exercitationem, quo cupiditate placeat culpa maiores vero vitae possimus! Velit veniam facere corporis consectetur.</p><br>

            <div class="container-paragraf-tiga-topic">
                <div class="paragraf-tiga-left">
                    <img 
                        class="image-topic"
                        src="~/assets/image/Graduation 1.png" 
                        alt="image not found"
                        style="max-width:400px;"
                    >
                </div>
                <div class="paragraf-tiga-right">
                    <p class="paragraf-tiga-topic">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque velit dolorum voluptates doloribus odit vel quos hic! Similique recusandae nulla, praesentium consequatur facilis veniam enim rerum necessitatibus, dolore obcaecati minima!. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur, consequatur deleniti ipsam quis minima dolor incidunt ut iusto amet repudiandae hic possimus, asperiores provident? Distinctio in sapiente eaque beatae illo? Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsum culpa accusantium porro deserunt temporibus sit commodi laborum quo eveniet. Accusantium quidem, amet dolorem accusamus reprehenderit consequatur ea a quis tenetur. Lorem ipsum, dolor sit amet consectetur adipisicing elit. . 
                    </p><br>
                    
                </div>
            </div>

            <p class="paragraf-empat-topic">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maxime reprehenderit sequi voluptates enim odio id corporis. Tempore qui a maxime repudiandae sequi vel deleniti reprehenderit, accusamus eos, consequuntur error amet? Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptates animi atque quia eos deleniti vitae voluptas, provident beatae quis voluptate nostrum pariatur, officiis magnam repudiandae quam similique, delectus dolorem labore?</p><br>

            <p class="paragraf-lima-topic">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magni dolorem excepturi esse! Blanditiis vero possimus tenetur ipsam magnam cumque eum dolor, fugiat ducimus. Dolorum laboriosam qui sequi repellendus? Eius, cum? Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil molestias delectus tempore eos laudantium quas obcaecati nesciunt debitis doloribus cumque, maiores voluptates magni rem illum quos modi, quasi placeat vero?</p><br>

            <p class="paragraf-enam-topic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laudantium debitis natus at facilis in iusto. Veritatis dolorem aperiam explicabo numquam ipsa non, sapiente recusandae, aut a magni, hic cumque?Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus animi, nesciunt cumque dicta vero quas numquam qui voluptas facilis, distinctio praesentium ipsam aperiam accusamus corporis autem doloribus incidunt assumenda deleniti?
            </p>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.jumbotron-container {
    width: 90%;
    margin-left: 5%;
}
.jumbotron-image {
    width: 100%!important;
}


/* Topic css */

.container-topic {
    width: 90%;
    margin-left: 5%;
    margin-top: 50px;
}
.title-topic {
    text-align: center;
    margin-bottom: 100px;
}
.paragraf-satu-topic,
.paragaraf-dua-topic,
.paragraf-tiga-topic,
.paragraf-empat-topic,
.paragraf-lima-topic,
.paragraf-enam-topic {
    font-size: 22px;
    /* margin-top: 100px; */
}

.container-paragraf-tiga-topic {
    width: 100%; 
    /* display: flex; */
    
}
.image-topic {
    width: 500px;
}
@media(min-width:1300px) {
    .container-paragraf-tiga-topic {
        display: flex;
    }
    .image-topic {
        margin-left: 50px;
    }
    .paragraf-tiga-topic {
        margin-left: 100px;
    }
}
@media (max-width: 768px) {
    .container-paragraf-tiga-topic {
        display: block;
        width: 100%;

    }
    .paragraf-satu-topic {
        margin-top: 10px                                                                                                                                                                                                     b;
    }
    .title-topic {
        font-size: 32px;
    }
    .paragraf-tiga-topic {
        margin-left: 0px;
    }
    .paragraf-satu-topic,
    .paragaraf-dua-topic,
    .paragraf-tiga-topic,
    .paragraf-empat-topic,
    .paragraf-lima-topic,
    .paragraf-enam-topic {
        font-size: 18px;
        /* margin-top: 100px; */
    }
    .image-topic {
        margin-left: 0;
        width: 300px;
    }
}


/* Footer pages 2 css */

.footer-container {
    background-color: #F8F9FA;
    margin-top: 100px;
    padding-top: 50px;
}
.medsos-content {
    display: flex;
}
.footer-image {
    width: 40px;
}

.first-footer-paragraf,
.second-footer-paragraf,
.medsos-content-paragraf {
    font-size: 18px;
}

.first-footer-paragraf,
.footer-image,
.second-footer-address,
.second-footer-paragraf {
    margin-top: 10px;
}
.medsos-content-paragraf {
    margin-top: 15px;
    margin-left: 10px;
}
.third-footer {
    background-color: #E2E2E2;
    padding-top: 5px;
}
.third-footer-content {
    text-align: center;
}
@media (min-width: 800px) {
    .third-footer {
        margin-top: 70px;
        height: 50px;
    }
    .footer-content {
        width: 80%;
        margin-left: 10%;
        display: flex;
        justify-content: space-between;
    }
    .first-footer {
        width: 450px;
        margin-top: 70px;
    }
    .second-footer {
        width: 350px;
        margin-top: 70px;
    }
    .third-footer-content {
        width: 80%;
        margin-left: 10%;
        padding-top: 10px;
    }
}
@media (max-width: 800px) {
    .footer-container {
        width: 100%!important;
    }
    .first-footer,
    .second-footer,
    .medsos-content {
        width: 90%;
        justify-content: center;
        margin-left: 5%;
    }
    .third-footer {
        width: 100%;
    }
    .third-footer-content {
        width: 90%;
        text-align: center;
    }
}
</style>