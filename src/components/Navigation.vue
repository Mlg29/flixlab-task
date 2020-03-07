<template>
    <div>
      <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light ">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Why Paystack
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <div class="dp">
                            <div>
                                <div class="dp-menu">
                                    <a class="dropdown-item" href="#"><img src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583331478/paystack/why_choose_paystack_db_iaxiow.svg" width="40" ></a>
                                    <div class="dp-item">
                                        <a class="dropdown-item" href="#"><p class="entre">Why Choose Paystack</p></a>
                                        <a class="dropdown-item" href="#">Over 60,000 businesses trust<br> paystack. Here's why.</a>
                                    </div>
                                    
                                </div>
                                <div class="dp-menu">
                                    <a class="dropdown-item" href="#"><img src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583331478/paystack/why_choose_paystack_db_iaxiow.svg" width="40" ></a>
                                    <div class="dp-item">
                                        <a class="dropdown-item" href="#"><p class="entre">Success Rate</p></a>
                                        <a class="dropdown-item" href="#">Get the best transaction success<br> rate in the industry</a>
                                    </div>
                                    
                                </div>
                                <div class="dp-menu">
                                    <a class="dropdown-item" href="#"><img src="https://res.cloudinary.com/dnmpnu3j6/image/upload/v1583331478/paystack/why_choose_paystack_db_iaxiow.svg" width="40" ></a>
                                    <div class="dp-item">
                                        <a class="dropdown-item" href="#"><p class="entre">Demo</p></a>
                                        <a class="dropdown-item" href="#">See the Paystack Checkout Form<br> and Dashboard in action</a>
                                    </div>
                                
                                </div>
                            </div>
                            
                            <div class="growth-div">
                                <p class="growth">YOUR GROWTH STAGE</p>
                                <h1 class="entre">For Entrepreneurs</h1>
                                <h1 class="entre">For Corporates</h1>
                                <h1 class="entre">For Global Brands</h1>

                                <p class="growth2">YOUR BUSINESS TYPE</p>
                                <h1 class="entre">For Fintechs</h1>
                                <h1 class="entre">For Schools</h1>
                                <h1 class="entre">For Betting</h1>
                            </div>
                        </div>
                        
                        
            
                    </div>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Customers</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Pricing</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Learn
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <a class="dropdown-item" href="#">Action</a>
                    <a class="dropdown-item" href="#">Another action</a>
                    <div class="dropdown-divider"></div>
                    <a class="dropdown-item" href="#">Something else here</a>
                    </div>
                </li>
                <div class="navi2">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Developers
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Action</a>
                        <a class="dropdown-item" href="#">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Support
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Action</a>
                        <a class="dropdown-item" href="#">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">Develop</a>
                    </li>
                    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Create free account</button>
                </div>
            </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Navigation",

}
</script>

<style scoped>
    .navi2 {
        display: flex;
        flex-direction: row;
        margin-left: 30rem
        }
        .navbar-light .navbar-nav .nav-link {
            color: rgb(28, 26, 104);
        }
        .dp {
            display: flex;
            flex-direction: row;
            }
        .dp-menu {
            display: flex;
            flex-direction: row;
            width: 20%
            }
        .growth {
            font-size: 12px;
            }
        .growth2 {
            font-size: 12px;
            margin-top: 2rem;
            }
        .entre {
            font-size: 15px;
            color: blue
            }
        /* .dp-item {
            width: 200px;
            } */

        .growth-div {
            width: 150px;
            background: lightgrey;
            margin-top: -2%;
            padding-top: 5%;
            margin-bottom: -2%;
            }
</style>