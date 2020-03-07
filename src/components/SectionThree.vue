<template>
    <div class="section-three">
        <div class="section-three-div">
            <h1 class="section-three-header">Build custom payments experiences with well-documented APIs</h1>
            <p class="section-three-paragraph">Developers love our thorough, well-documented APIs that let you to build everything from simple weekend projects, to complex financial products serving hundreds of thousands of customers. If you can imagine it, you can build it with Paystack.</p>
            <div class="section-three-div_div">
                <div class="section-three-sub-div">
                    <img class="section-three-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                    <p class="section-three-dub-paragraph">Collect one-time and recurring payments from your app or website</p>
                </div>
                <div class="section-three-sub-div">
                    <img class="section-three-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                    <p class="section-three-dub-paragraph">Make instant transfers</p>
                </div>
                <div class="section-three-sub-div">
                    <img class="section-three-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                    <p class="section-three-dub-paragraph">Retrieve all your transaction and customer data</p>
                </div>
                <div class="section-three-sub-div">
                    <img class="section-three-icon" src="https://img.icons8.com/material/30/00FF00/checkmark--v1.png">
                    <p class="section-three-dub-paragraph">Verify the identity of customers</p>
                </div>
            </div>
            <a href="" class="section-three-link"><p><img class="greater-than" src="https://img.icons8.com/material/14/00FF00/more-than--v2.png"> Paystack API Quickstart</p></a>
        </div>
        <img class="section-three-image" src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583319728/paystack/Robust-Suite-of-APIs-Opt_ywtyu8.png" width="500">
    </div>
</template>

<script>
export default {
    name: 'SectionThree'
}
</script>

<style scoped>
    .section-three {
        display: flex;
        flex-direction: row;
        padding: 0% 10% 3% 10%
    }
    .section-three-header {
        font-weight: bold;
        color: rgb(19, 19, 54);
    }
    .section-three-paragraph {
        font-weight: 500;
        font-size: 20px;
        margin-top: 3%;
        line-height: 30px;
        color: rgb(19, 19, 54);
    }
    .section-three-sub-div {
        display: flex;
        flex-direction: row;
    }
    .section-three-div_div {
        margin-top: 6%;
    }
    .section-three-dub-paragraph {
        color: rgb(19, 19, 54);
        font-weight: 500;
    }
    .section-three-image {
        margin-left: 15%
    }
    .section-three-link {
        color: rgb(38, 128, 86);
        font-weight: bold;
    }
    .section-three-icon {
        margin-top: -3%;
    }
    .greater-than {
        border: 1px solid #00FF00;
        border-radius: 50%;
    }

    @media screen and (min-width: 320px) and (max-width: 450px) {
        .section-three {
            display: flex;
            flex-direction: column-reverse;
            padding: 1.5%;
        }
        .section-three-image {
            margin-left: 0%;
            width: 100%;
        }
        .section-three-header {
            width: 100%;
            font-size: 20px;
            margin-top: 8%;
        }
        .section-three-paragraph {
            font-size: 13px;
            line-height: 25px;
            margin-top: 5%;
        }
    }
</style>