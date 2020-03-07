<template>
    <div class="section-four">
        <img class="section-four-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583440704/paystack/Capture_mulrnu.png">
        <div class="section-four-div">
            <h1 class="section-four-header">Protect yourself and your customers with advanced fraud detection</h1>
            <p class="section-four-paragraph">Paystack’s combination of automated and manual fraud systems protect you from fraudulent transactions and associated chargeback claims.</p>
            
            <h1 class="section-four-header2">Detailed reporting for accounting, reconciliation, and audits</h1>
            <p class="section-four-paragraph">Understand your customers’ purchase patterns and do easy reconciliations with a robust data Dashboard and easy exports.</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SectionFour'
}
</script>

<style scoped>
    .section-four {
        display: flex;
        flex-direction: row;
        padding: 10%;
    }
    .section-four-div {
        margin-left: 10%
    }
    .section-four-header {
        color: rgb(19, 19, 54);
        font-weight: bold;
        width: 80%;
    }
    .section-four-header2 {
        color: rgb(19, 19, 54);
        font-weight: bold;
        margin-top: 15%;
        width: 80%;
    }
    .section-four-paragraph {
        font-size: 20px;
        line-height: 40px;
        color: rgb(19, 19, 54);
        width: 80%;
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-four {
            padding: 1.5%;
            display: flex;
            flex-direction: column;
        }
        .section-four-div {
            display: flex;
            flex-direction: column;
        }
        .section-four-image {
            width: 100%;
        }
        .section-four-header {
            width: 100%;
            font-size: 25px;
            margin-top: 4%;
        }
        .section-four-paragraph {
            width: 100%;
            font-size: 15px;
            line-height: 25px;
        }
        .section-four-header2 {
            width: 100%;
            font-size: 25px;
        }
        .section-four-div {
            margin-left: 1%;
        }
    }
</style>