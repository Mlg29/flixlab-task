<template>
    <div class="section-two">
        <h1 class="section-two_header">Simple, easy payments</h1>
        <p class="section-two-paragraph">Building a business is hard. Getting paid shouldn't be.</p>
        <div class="section-two-div">
            <img class="section-two-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319726/paystack/Collect-Payments-for-Multiple-Channels-1.1_axdbpb.gif" width="600">
            <div class="section-two-div_div">
                <h1 class="section-two-div_div_header">Delight customers with a seamless payments experience</h1>
                <p class="section-two-div_div_paragraph">Give your customers the gift of modern, frictionless, painless payments. Integrate Paystack once and let your customers pay you however they want.</p>
                <div class="section-two-sub_div">
                    <div class="section-two-sub-div_div">
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>Card</p>
                        </div>
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>Bank Account</p>
                        </div>
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>GTB 737</p>
                        </div>
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>Visa QR</p>
                        </div>
                        
                    </div>
                    <div>
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>Mobile Money</p>
                        </div>
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>mCash (Coming soon)</p>
                        </div>
                        <div class="section-two-row-div">
                            <img class="section-two-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                            <p>POS (Coming soon)</p>
                        </div>
                    </div>
                </div>
                <div class="section-phenomenal">
                    <h1 class="phenomenal-header">Enjoy phenomenal transaction success rates</h1>
                    <p class="phenomenal-paragraph">We automatically route payments through the most optimal channels, ensuring the highest transaction success rates in the market.</p>
                    <a href="" class="phenomenal-link"><p><img class="greater-than" src="https://img.icons8.com/material/14/00FF00/more-than--v2.png"> Find out how we achieve high success rates</p></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SectionTwo'
}
</script>

<style scoped>
    .section-two {
        display: flex;
        flex-direction: column;
        padding: 10%;
    }
    .section-two-div {
        display: flex;
        flex-direction: row;
        margin-top: 10%
    }
    .section-two-div_div {
        display: flex;
        flex-direction: column;
        margin-left: 5%
    }
    .section-two_header {
        font-size: 40px;
        font-weight: bold;
        color: rgb(19, 19, 54);
    }
    .section-two-paragraph {
        font-size: 19px;
        font-weight: 500;
        color: rgb(19, 19, 54);
    }
    .section-two-div_div_header {
        color: rgb(19, 19, 54);
        font-weight: bolder;
        width: 82%;
    }
    .section-two-div_div_paragraph {
        color: rgb(19, 19, 54);
        font-weight: 400;
        margin-top: 2%;
        line-height: 30px;
        font-size: 20px;
        width: 80%;
    }
    .section-two-sub_div {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-top: 4%;
        width: 80%;
    }
    .section-two-row-div {
        display: flex;
        flex-direction: row;
    }
    .section-phenomenal {
        margin-top: 5%;
        width: 100%;
    }
    .phenomenal-header {
        color: rgb(19, 19, 54);
        font-weight: bold;
        width: 80%;
    }
    .phenomenal-paragraph {
        color: rgb(19, 19, 54);
        font-weight: 400;
        font-size: 20px;
        line-height: 30px;
        width: 80%;
    }
    .phenomenal-link {
        color: rgb(38, 128, 86);
        font-weight: bold
    }
    .section-two-icon {
        margin-top: -10%;
    }
    .greater-than {
        border: 1px solid #00FF00;
        border-radius: 50%;
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-two {
            padding: 1.5%;
        }
        .section-two_header {
            font-size: 30px;
        }
        .section-two-paragraph {
            font-size: 15px;
            width: 100%;
            margin-top: 4%;
        }
        .section-two-div {
            display: flex;
            flex-direction: column;
        }
        .section-two-image {
            width: 100%;
        }
        .section-two-div_div {
            width: 100%;
            margin-top: 10%;
        }
        .section-two-div_div_header {
            width: 100%;
            font-size: 21px;
            margin-top: 3%;
        }
        .section-two-div_div_paragraph{
            width: 100%;
            font-size: 15px;
            margin-top: 3%;
        }
        .section-two-sub_div {
            display: flex;
            flex-direction: column;
           
        }
        .phenomenal-header {
            color: rgb(19, 19, 54);
            font-size: 22px;
            font-weight: bold;
            width: 100%;
        }
        .phenomenal-paragraph {
            color: rgb(19, 19, 54);
            font-weight: 400;
            font-size: 15px;
            line-height: 30px;
            width: 100%;
    }
    }
</style>