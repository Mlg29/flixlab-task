<template>
    <div>
        <div class="payment-component">
            <img :src="img" width="100px">
            <h1 class="payment-header">{{header}}</h1>
            <p class="payment-text">{{text}}</p>
            <a href=""><p class="payment-link">{{link}}</p></a>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PaymentComponent',
    props: {
        img: String,
        header: String,
        text: String,
        link: String
    }
}
</script>


<style scoped>
    .payment-component {
        padding: 7%;
        width: 95%;
        height: 350px;
        background: white;
        border-radius: 5px;
    }
    .payment-header {
        font-size: 20px;
        width: 60%;
        font-weight: bold;
        margin-top: 5%;
        color: rgb(19, 19, 54);
    }
    .payment-text {
        font-size: 16px;
        margin-top: 5%;
        width: 70%;
        line-height: 25px;
        color: rgb(19, 19, 54);
        font-weight: 400;
    }
    .payment-link {
        color: rgb(19, 19, 54);
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .payment-component {
            height: 400px;
        }
        .payment-header {
            width: 75%;
        }
        .payment-text {
            width: 100%;
        }
    }
</style>