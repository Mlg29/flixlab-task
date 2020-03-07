<template>
    <div class="section-five">
        <div class="section-five-div">
            <h1 class="section-five-header">Trusted by 60,000+ businesses</h1>
            <p class="section-five-paragraph">Thousands of organizations of all sizes trust Paystack to grow their business. </p>
        </div>
        <div class="section-five-div2">
            <PaymentComponent 
                img='https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319725/paystack/For-International-Businesses_180823_165939_ust9zs.svg'
                header='Paystack for Global Brands'
                text='We help global brands accept payments from across Africa'
                link='Learn More'
            />
            <PaymentComponent 
                img='https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319725/paystack/For-Entrepreneurs_180823_165709_cmdf1n.svg'
                header='Paystack for Entrepreneurs'
                text='From startup to scale-up, we can support you at every stage of your businesses’ growth'
                link='Learn More'
            />
            <PaymentComponent 
                img='https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319726/paystack/For-Large-Corporations_180823_165502_awwbbz.svg'
                header='Paystack for Large Organizations'
                text='Paystack helps many of the largest corporate and government organizations in Nigeria get paid quickly and securely.'
                link='Learn More'
            />
        </div>
    </div>
</template>

<script>
import PaymentComponent from "./PaymentComponent"

export default {
    name: 'SectionFive',
    components: {
        PaymentComponent,
    }
}
</script>

<style scoped>
    .section-five {
        padding: 10%;
        background: rgb(197, 240, 240);
        width: 100%;
    }
    .section-five-header {
        font-size: 45px;
        font-weight: bold;
    }
    .section-five-paragraph {
        font-size: 20px;
        font-weight: 400;
        width: 50%;
    }
    .section-five-div2 {
        display: flex;
        flex-direction: row;
        margin-top: 4%;
        
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-five {
            padding: 15% 1.5% 1.5% 3.5%;
            height: 95rem;
        }
        .section-five-header {
            font-size: 25px;
            width: 70%;
        }
        .section-five-paragraph {
            width: 100%;
            font-size: 15px;
        }
        .section-five-div2 {
            display: flex;
            flex-direction: column;
            margin-top: 15%;
        }
    }
</style>