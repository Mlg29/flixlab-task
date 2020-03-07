<template>
    <div class="section-six">
        <h1 class="section-six-header">Powering growth for amazing businesses</h1>
        <p class="section-six-paragraph">Paystack is a growth engine for a new generation of innovative, forward-looking organizations operating in Africa.</p>
        <div class="section-six-div">
            <div class="section-six-sub_div">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524159/paystack/Air-Peace-Stack-Blue_200305_154114_cf2h6b.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524166/paystack/FilmHouse-Stack-Blue_200304_153641_l08zza.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524172/paystack/Piggyvest-Stack-Blue_200304_153734_wmbr8v.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524169/paystack/Ibom-Air-Stack-Blue_200304_154259_rad2ff.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524170/paystack/kuda-Stack-Blue_200304_154345_ijct44.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524159/paystack/Ariiya-Stack-Blue_200304_155307_qykuiz.svg">
            </div>
             <div class="section-six-sub_div">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524166/paystack/Dominos-Plain_yknt7u.svg" width="200px">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524171/paystack/MTN-Plain_t3c3no.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524170/paystack/Lagos-Internal-Revenue-Service_i9pu2b.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524159/paystack/Bolt-Stack-Blue_200304_153027_dtslb9.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524159/paystack/Betway-Plain_lm5g8y.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524163/paystack/carbon-dark_lypxhs.svg">
            </div>
             <div class="section-six-sub_div">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524159/paystack/Axa-mansard-_-Plain_hcfytp.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524159/paystack/Abia-State-University_igpa3o.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524166/paystack/GIGM-Plain_180827_172142_zsltzx.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524169/paystack/IrokoTV-Plain_rb2is4.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524172/paystack/Smile-Plain_180827_172218_ndbfdr.svg">
                <img class="section-six-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583524165/paystack/Cowrywise-dark_qmysqj.svg">
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'SectionSix'
}
</script>


<style scoped>
    .section-six {
        padding: 10%;
    }

    .section-six-div {
        width: 100%;
        
    }
    .section-six-header {
        width: 60%;
        font-size: 45px;
        font-weight: bold;
    }
    .section-six-paragraph{
        width: 50%;
        font-size: 20px;
        font-weight: 500;
        margin: 2% 0%;
    }
    .section-six-sub_div {
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        margin-top: 5%;
    }
    .section-six-image {
        width: 50px;
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-six {
            padding: 1.5%;
            margin-top: 15%;
        }
        .section-six-header {
            width: 100%;
            font-size: 35px;
        }
        .section-six-paragraph {
            width: 100%;
            font-size: 15px;
            line-height: 25px;
            font-weight: 400;
        }
        .section-six-div {
            display: none;
        }
    }
    
</style>