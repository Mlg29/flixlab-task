<template>
<div class="section-one">
    <div>
        <h1 class="section-one-header">Modern online and offline payments for Africa
        </h1>
        <p class="section-one-paragraph">Paystack helps businesses in Africa get paid by anyone, anywhere in the world</p>
        <button type="button" class="section-one-button">Create a free account</button>
    </div>
    <div class="section-one-div">
        <div>
            <p class="section-one-div_header">Trusted by over 60,000 businesses</p>
            <div class="section-one-div_div">
                <img class="section-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319725/paystack/Dominos-Plain_boyxd9.svg" width="150">
                <img class="section-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319727/paystack/MTN-Plain_qildhn.svg" width="100">
                <img class="section-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583425331/paystack/Bolt-Stack-Blue_eskoqn.svg" width="50">
                <img class="section-image2" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583425331/paystack/Axa-mansard-_-Plain_yqk4tm.svg" width="150">
            </div>
        </div>
        <div class="section-one-div2">
            <p class="section-one-div2_paragraph">Watch MTN Chief Transformation Officer, Olubayo Adekambi, discuss working with Paystack</p>
            <img src="">
        </div>
        
    </div>
</div>
    
</template>

<script>
export default {
    name: "SectionOne",
    
}
</script>

<style scoped>
    .section-one {
        padding: 10% 10% 3% 10%;
        background: rgb(213, 236, 231);
        height: 100%;
    }
    .section-one-header {
        font-size: 50px;
        font-weight: bold;
        width: 50%;
    }
    .section-one-paragraph {
        font-weight: 500;
        font-size: 20px;
        margin-top: 15px;
        width: 40%;
    }
    .section-one-button {
        padding: 10px;
        width: 250px;
        border-radius: 10px;
        border: none;
        color: white;
        background: rgb(67, 190, 67);
    }
    .section-one-div {
        margin-top: 15%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    .section-one-div_header {
        font-weight: 600;
    }
    .section-one-div_div {
        margin-top: -2%;
    }
    .section-image {
       margin-right: 15px;
    }
    .section-one-div2_paragraph {
        font-weight: 600;
        width: 60%;
        margin-left: 35%;
    }


    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-one {
            padding: 1.5%;
        }
         .section-one-header {
            font-size: 25px;
            font-weight: bold;
            width: 100%;
            padding-top: 25%;
        }
        .section-one-paragraph {
            font-weight: 400;
            font-size: 15px;
            margin-top: 15px;
            width: 100%;
        }
        .section-one-div {
            margin-top: 30%;
            display: flex;
            flex-direction: column;
        }
        .section-one-div_header {
            width: 100%;
            font-size: 15px;
        }
        .section-image {
        margin-right: 15px;
        width: 20%;
        }
        .section-image2 {
            display: none;
        }
        .section-one-div2_paragraph {
            font-weight: 600;
            font-size: 15px;
            width: 100%;
            margin-top: 10%;
            margin-left: 0;
        }
    }
</style>