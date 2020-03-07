<template>
    <div class="section-seven">
        <h1 class="seven-header">Backed by strong global partners</h1>
        <p class="seven-paragraph">Paystack is backed by notable investors as well as some of the best payments companies on the planet.</p>
        
        <div class="seven-div">
            <div class="seven-sub_div">
                <img class="seven-image1" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319729/paystack/Stripe-Logo-blue_skdypi.png" />
                <p class="seven-sub-paragraph">Paystack is highly technical and fanatically customer oriented. We’re excited to back such people in one of the world’s fastest-growing regions.</p>
                <div class="seven-sub-div-div"> 
                    <img class="seven-image2" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319729/paystack/patrick-collison-headshot_cdaung.jpg" />
                    <div class="seven-sub-div-sub">
                        <h1 class="seven-sub-div-sub-header">Patrick Collison</h1>
                        <p class="seven-sub-div-sub-paragraph">CEO, Stripe</p>
                    </div>
                </div>
            </div>
            <div class="seven-sub_div">
                <img class="seven-image1" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319729/paystack/visa-logo_mnqmnf.png" />
                <p class="seven-sub-paragraph">Our investment in Paystack aligns with the kind of investments we look for - those that will help extend our reach into the global commerce ecosystem</p>
                <div class="seven-sub-div-div">
                    <img class="seven-image2" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319727/paystack/otto-williams_ig84uy.jpg" />
                    <div class="seven-sub-div-sub">
                        <h1 class="seven-sub-div-sub-header">Otto Williams</h1>
                        <p class="seven-sub-div-sub-paragraph">Head of Strategic Partnerships, Fintech & Ventures CEMEA, Visa</p>
                    </div>
                </div>
            </div>
            <div class="seven-sub_div">
                <img class="seven-image3" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319729/paystack/ycombinator-logo_pmg97v.png" />
                <p class="seven-sub-paragraph">As YC's first Nigerian startup Paystack leads the charge of great companies coming out of Africa, powering modern payments for an entire continent.</p>
                <div class="seven-sub-div-div">
                    <img class="seven-image2" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319727/paystack/michael-siebel-headshot_wehroq.jpg" />
                    <div class="seven-sub-div-sub">
                        <h1 class="seven-sub-div-sub-header">Michael Seibel</h1>
                        <p class="seven-sub-div-sub-paragraph">CEO, Partner, Y Combinator</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SectionSeven'
}
</script>

<style scoped>
    .section-seven {
        padding: 10%;
        background: rgb(237, 242, 252);
    }
    .seven-header {
        font-size: 50px;
        font-weight: bold;
        width: 60%;

    }
    .seven-div {
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
    }
    .seven-image1 {
        width: 60px;
    }
    .seven-image3 {
        width: 40px;
        height: 40px;
    }
    .seven-image2 {
        width: 50px;
        height: 50px;
        border-radius: 50%;
    }
    .seven-paragraph {
        width: 50%;
        font-size: 20px;
        margin-top: 3%;
        margin-bottom: 3%;
    }
    .seven-sub_div {
        background: white;
        border-radius: 10px;
        width: 30%;
        padding: 20px;
    }
    .seven-sub-paragraph {
        margin-top: 5%;
    }
    .seven-sub-div-div {
        display: flex;
        flex-direction: row; 
        margin-top: 15%;
    }
    
    .seven-sub-div-sub-header {
        font-size: 18px;
    }
    .seven-sub-div-sub-paragraph {
        font-size: 12px;
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-seven {
            padding: 10% 1.5%;
        }
        .seven-header {
            width: 100%;
            font-size: 30px;
        }
        .seven-paragraph {
            width: 100%;
            font-size: 19px;
        }
        .seven-div {
            display: flex;
            flex-direction: column;
            width: 100%;
            margin-top: 15%;
        }
        .seven-sub_div {
            width: 95%;
            margin: 2% auto;
        }
    }
</style>