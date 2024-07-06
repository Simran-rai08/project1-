<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Web.css">
    <script src="https://kit.fontawesome.com/f30fac2c61.js" crossorigin="anonymous"></script>
    <link
        href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Catamaran:wght@200&family=Courgette&family=Edu+TAS+Beginner:wght@700&family=Lato:wght@300;900&family=Mukta:wght@700&family=Mulish:wght@300&family=Open+Sans&family=PT+Sans:ital,wght@1,700&family=Poppins:wght@300&family=Raleway:wght@100&family=Roboto&family=Roboto+Condensed:wght@700&family=Roboto+Slab&display=swap"
        rel="stylesheet">
</head>

<body>
    <div class="container">
        <nav>
            <div class="logo">
                <h1>Trends</h1>
            </div>
            <ul>
                <li>
                    <a id="home" onclick="homes()">Home</a>
                    <a id="shop" onclick="shops()">Shops</a>
                    <a id="blog" onclick="blogs()">Blog</a>
                    <a id="about" onclick="abouts()">About</a>
                    <a id="contact" onclick="contacts()">Contact</a>
                    <i class="fa-sharp fa-solid fa-cart-shopping"></i>

                </li>
            </ul>
        </nav>

        <!-- mainpage -->

        <div class="main">
            <div class="mainText">
                <h2>Trends</h2>
                <h1 class="top">Super Value Deals</h1>
                <h1>On All Products</h1>
                <p>Embroider your heart into the fabric of your clothes.</p>
                <button>Explore</button>
            </div>
            <img src="m3.png" alt="">
        </div>

        <!-- cards -->

        <div class="trend">
            <div class="head">
                <h1>Trends <span>Men's Wear</span></h1>
            </div>
            <div class="card">
                <div class="crd">
                    <img src="srt1.webp" alt="" onclick="show(this)">
                    <div class="crdText">
                        <h2>Cotton Trending Shirt's</h2>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half-stroke"></i> <br>
                        <button>Add to Cart</button>
                    </div>
                 </div>

                 <div class="crd">
                    <img src="srt2.webp" alt="" onclick="show(this)">
                    <div class="crdText">
                        <h2>Cotton Trending Shirt's</h2>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half-stroke"></i> <br>
                        <button>Add to Cart</button>
                    </div>
                 </div>
                    <div class="crd">
                        <img src="srt6.webp" alt="" onclick="show(this)">
                        <div class="crdText">
                            <h2>Cotton Trending Shirt's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>

                <!-- Women Card -->

                <div class="trend" id="trendSec">
                    <div class="head">
                        <h1>Trends <span>Women's Wear</span></h1>
                    </div>
                    <div class="card">
                        <div class="crd">
                            <img src="wn4.webp" alt="" onclick="show(this)">
                            <div class="crdText">
                                <h2>Trending Girl Top's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                            </div>
                        </div>

                        <div class="crd">
                            <img src="wn5.webp" alt="" onclick="show(this)">
                            <div class="crdText">
                                <h2>Trending Girl Top's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                            </div>
                        </div>

                        <div class="crd">
                            <img src="wn6.webp" alt="" onclick="show(this)">
                            <div class="crdText">
                                <h2>Trending Girl Top's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                            </div>
                        </div>
                    </div>
                </div>


                <!-- about us -->

                <div class="about">

                    <div class="aboutus">
                        <h1>#KnowUs</h1>
                        <p>provide Best facility </p>
                    </div>

                    <div class="me">
                        <img src="lap.png" alt="">
                        <div class="aboutText">
                            <h1>Who we are ?</h1>
                            <p>It can be difficult to articulate the power of style and fashion through words, 
                             but these icons managed to do so with quote-worthy, inspiring words of wisdom to live
                              by. From the greatest fashion designers to legendary models and stylists, 
                              get inspired by these which  will never go out of style..</p>
                        </div>
                    </div>
                </div>

                <!-- contact -->

                <div class="contact">

                    <div class="contactus">
                        <h1>#Let's Connect</h1>
                        <p>24/7 customer support is a your policy.</p>
                    </div>

                    <div class="contactMe">
                        <div class="contactText">
                            <h1>Visit Our Office or Contact <br>
                                Us Today</h1>
                            <p>Address : Dablin Park, England, New york.</p>
                            <p>Contact : dumiemail@gmail.com</p>
                            <p>Number : +198560386496</p>
                        </div>
                        <img src="map.PNG" alt="">
                    </div>

                    <div class="form">
                        <h1>Connect with Us. Fill Form</h1>
                        <input type="text" placeholder="Enter Email"> <br>
                        <input type="password" placeholder="Enter password"> <br>
                        <button>Submit</button>

                    </div>
                </div>
                 <!-- cart -->

                 <div class="cart">
                    <img id="newImg" src="" alt="">
                    <div class="cartText">
                        <h1>Trends Offer : Trending Shop <br>
                            Now</h1>
                            <h2>Special Price</h2>
                            <h2>$11</h2>
                         <p> Whether you’re creating a casual outfit to hang out with friends or need layers 
                         under your flannel in the fall, there are a many clothes that styles to add to your
                         wardrobe</p>
                           <div class="btn">
                            <button>Buy Now</button>
                            <button onclick="addCart()">Add to Cart</button>
                           </div>
                           <button  class="back">Back</button>



                    </div>
                 </div>

                <!-- blogs -->
                <div class="trends">
                    <div class="head">
                        <h1>Trends <span>Men's Wear</span></h1>
                    </div>
                    <div class="card">
                        <div class="blog">
                            <img src="tr1.webp" alt="">
                            <div class="blogText">
                                <h2>Trending Girl Clothes</h2>
                                <p>The most oft-spotted trend of the  runways might just be
                                     the fashion trend that's undergone the most drastic evolution—sheer dressing. 
                                   </p>
                                <a href="https://influencermarketinghub.com/best-fashion-blogs/">Read More</a>
                            </div>
                        </div>

                        <div class="blog">
                            <img src="tr3.webp" alt="">
                            <div class="blogText">
                                <h2>Trending Boys Clothes</h2>
                                <p>Simple and casual, guys can’t go wrong with quality clothes. Whether you’re 
                                    creating a casual outfit to hang out with friends or need layers under your 
                                    flannel in the fall, there are many different clothes styles to add to your
                                     wardrobe</p>
                                <a href="https://www.apetogentleman.com/">Read More</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Letter -->

                <div class="letter">
                    <div class="letterText">
                        <h1>Sign Up for NewsLetter</h1>
                    </div>
                    <div class="inp">
                        <input type="text" placeholder="Enter Email">
                        <button>Sign Up</button>
                    </div>
                </div>

                <!-- Footer -->

                <div class="footer">
                    <div class="footerText">
                        <h2>Trends</h2>
                        <p>Service </p>
                        <p>Customer</p>
                        <p>Satisfaction</p>
                        <p></p>

                    </div>
                    <div class="footerText">
                        <h2>About US</h2>
                        <p>Adrress : 19 Saxon St. <br>
                              Fairport, NY 14450 <br>
                        </p>
                        <p>Service</p>
                        <p>Customer</p>
                        <p>Satisfation</p>

                    </div>
                    <div class="footerText">
                        <h2>Contact</h2>
                        <p>+134579760598</p>
                        <p>Customer</p>
                        <p>Coming up</p>
                        <p>New Arrival</p>

                    </div>
                    <div class="footerText">
                        <h2>Trending</h2>
                        <p>Service</p>
                        <p>Customer</p>
                        <p>Shops</p>
                        <p></p>

                    </div>
                </div>
            </div>
            <script src="Web.js"></script>
</body>

</html>
