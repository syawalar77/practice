<template>
    <div class="footer-container" id="footer">
            <div class="footer-content">
                <div class="first-footer">
                    <h2 class="first-footer-title ">
                        Seakun.id
                    </h2>
                    <p class="first-footer-paragraf">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores est eius, eos vel officiis accusantium culpa ab doloribus harum alias cupiditate rem ut quis, in, ratione aspernatur inventore sed atque.
                    </p>
    
                </div>
                <div class="second-footer">
                    <div>
    
                        <div class="second-footer-medsos">
                            <h2>
                                Media Sosial
                            </h2>
                            <a href="https://www.instagram.com/_akbrswalarr/">
                            <img 
                                class="footer-image"
                                src="~/assets/image/image 6.png"
                                alt=""
                            >
                            </a>
                            <a href="https://www.facebook.com/syawal.cittruss">
                            <img 
                                class="footer-image"
                                src="~/assets/image/image 7.png" 
                                alt=""
                            >
                            </a>
    
                        </div>
                        <div class="second-footer-address">
                            <h2 class="second-footer-title ">
                                Alamat
                            </h2>
                            <p class="second-footer-paragraf">
                                Jl. Letda Sudjono No. 273, Medan Tembung Medan, Sumatera Utara
                            </p>
                        </div>
                    </div>
                    <div class="second-footer-contact">
                        <h2 class="">
                            Hubungi Kami
                        </h2>
                        <div class="medsos-content">
                            <img 
                                class="footer-image"
                                src="~/assets/image/Rectangle 7.png" 
                                alt=""
                            >
                            <a href="https://wa.me/6281397110834" class="medsos-content-paragraf">
                                081397110834
                            </a>
                        </div>
    
                    </div>
    
                </div>
            </div>
            <div class="third-footer">
                <p class="third-footer-content ">
                    © Copyright 2021 Seakun.id
                </p>
    
            </div>
    
        </div>
</template>

<script>
export default {

}
</script>

<style>
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