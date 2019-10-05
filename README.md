# eCommerce
This is an eCommerce website I have been working on.
This project is very significant to me because it took me weeks on the making trial and error different things.
Over time, I mastered the project that took place as a result of many skills picked up on udemy.com and codingphase.com.

The hamburger located at the left side upper corner works
The contact page (visible option when you click the hamburger) works.
The combination of css, html, js, and images work great.

Index

<!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <meta name="author" content="Belzarion - franguardado28@gmail.com">
      <link rel="icon" href="yourIconUrl" type="image/gif" sizes="16x16">
      <title>The Zurfaro - The website is designed by Zurfaro/Belzarion</title>


      <link rel="stylesheet" href="style.css">

      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

      <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>

      <link href="https://fonts.googleapis.com/css?family=Playfair+Display&display=swap" rel="stylesheet">

      <script src="https://code.jquery.com/jquery-3.4.1.js"></script>

      <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.2/TweenMax.min.js"></script>

      <link rel="stylesheet" href="animate.css">
      <script src="wow.min.js"></script>
</head>
<body>
      <div class="my-container">


            <div class="nav">
                  <div class="menu-open">
                        <ion-icon name="menu"></ion-icon>
                  </div>
                  <div class="brand">
                        <span><a href="index.html">The Zurfaro</a></span>
                  </div>
                  <div class="cart">
                        <ion-icon name="cart"></ion-icon>
                  </div>
                  <div class="menu">
                        <div class="menu-close">
                              <ion-icon name="close"></ion-icon>
                        </div>
                        <ul>
                              <li><a href="index.html">Home</a></li>
                              <li><a href="shop.html">collection</a></li>
                              <li><a href="product.html">Product</a></li>
                              <li><a href="about.html">Our story</a></li>
                              <li><a href="contact.html">Contact</a></li>
                        </ul>
                        <div class="media-menu">
                              <ul>
                                    <li><ion-icon name="logo-facebook"></ion-icon></li>
                                    <li><ion-icon name="logo-instagram"></ion-icon></li>
                                    <li><ion-icon name="logo-twitter"></ion-icon></li>
                                    <li><ion-icon name="logo-pinterest"></ion-icon></li>
                              </ul>
                        </div>
                  </div>
            </div>




            <div class="hero-section">
                  <div class="container-fluid">
                        <div class="row">
                              <div class="col-lg-6 hero-left">
                                    <div class="tagline">
                                          <p class="wow fadeInUp">Amazing engines to inspire <br> motivate, and multiply activity <br> ingenuity.</p>
                                    </div>



                                    <div class="shipping">
                                          <p class="wow fadeInUp" data-wow-delay="0.5s">Appreciative ground shipping on U.S. orders $50+ <br> Go and check what you want!!!</p>
                                    </div>
                              </div>

                              <div class="col-lg-6 hero-right">
                                    <div class="hero-image">
                                          <img src="images/hero.jpg" class="img wow fadeInUp" data-wow-delay="0.3s" alt="">
                                    </div>
                              </div>
                        </div>
                  </div>
            </div>



            <div class="section prod-list">
                  <div class="container-fluid">
                        <div class="row some-cards">
                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.3s">
                                    <a href="product.html">
                                          <p id="price"> VALERIE USD $20.00</p>
                                          <img src="images/prod-04.jpg" alt="">
                                          <p id="prod-desc">Day-to-day Administrator 2019 in Green</p>
                                    </a>
                              </div>
                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.8s">
                                    <a href="product.html">
                                          <p id="price"> DEVON USD $50.00</p>
                                          <img src="images/prod-05.jpg" alt="">
                                          <p id="prod-desc">Day-to-day Administrator 2019/2020 in Blue</p>
                                    </a>
                              </div>
                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="1.1s">
                                    <a href="product.html">
                                          <p id="price">GRIFFIN USD $20.00</p>
                                          <img src="images/prod-06.jpg" alt="">
                                          <p id="prod-desc">Day-to-day Administrator 2019 in Brown</p>
                                    </a>
                              </div>
                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="1.4s">
                                    <a href="product.html">
                                          <p id="price">LUKE USD $75.00</p>
                                          <img src="images/prod-07.jpg" alt="">
                                          <p id="prod-desc">Day-to-day Administrator in Dark Brown</p>
                                    </a>
                              </div>
                        </div>
                  </div>
            </div>



            <div class="row prod-sec">
                  <div class="col-lg-6 prod-img">
                        <img src="images/single-prod.jpg" alt="">
                  </div>

                  <div class="col-lg-4 prod-desc">
                        <br><br>
                        <p class="wow fadeInUp" data-wow-delay="0.5s">More doing and less talking is more useful. There is no tomorrow only the today and the now.</p>

                        <div class="link wow fadeInUp" data-wow-delay="0.6s">
                              <a href="shop.html">Go shopping <ion-icon name="arrow-round-forward"></ion-icon></a>
                        </div>
                  </div>
            </div>



            <div class="container-fluid">
                  <div class="row section shop">
                        <div class="col-lg-8">
                              <p class="wow fadeInUp" data-wow-delay="0.3s">What are you waiting for? time is always right. The place does not matter, the time does not matter, you have what you need right now and better thingd will come along. <br> It is important to visit this website everyday! </p>

                              <div class="link wow fadeInUp" data-wow-delay="0.3s">
                                    <a href="shop.html">Master more <ion-icon name="arrow-round-forward"></ion-icon></a>
                              </div>
                        </div>
                  </div>

                  <div class="container-fluid">
                        <div class="row some-cards">
                              <div class="col-lg-3"></div>

                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.3s">
                                    <img src="images/prod-01.jpg" alt="">
                                    <p id="prod-desc">Belzarion is a Youtube channel that started in 2019 with the purpose to entertain gamers!</p>
                              </div>

                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.3s">
                                    <img src="images/prod-02.jpg" alt="">
                                    <p id="prod-desc">The Zurfaro, is a station that represents being smart and creative. This channel is specifically made to educate web development and UI/UX!</p>
                              </div>

                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.3s">
                                    <img src="images/prod-03.jpg" alt="">
                                    <p id="prod-desc">Combine Belzarion and The Zurfaro, what you get is the right combination to never get bored!</p>
                              </div>
                        </div>
                  </div>
            </div>


            <br><br><br>


            <div class="container-fluid footer">
                  <div class="section container">
                        <footer>
                              <div class="row">
                                    <div class="col-lg-3 block">
                                          <p>The Zurfaro, 250 Rutherford,
                                          <br>
                                          Boston, MA. 02129,
                                          <br>
                                          USA</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <p>Corp
                                          <br>
                                          Return Policy
                                          <br>
                                          Shipping</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <p>Vanguard
                                          <br>
                                          Community
                                          <br>
                                          Innovation</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <div class="media">
                                                <ul>
                                                      <li><ion-icon name="logo-facebook"></ion-icon></li>
                                                      <li><ion-icon name="logo-instagram"></ion-icon></li>
                                                      <li><ion-icon name="logo-twitter"></ion-icon></li>
                                                      <li><ion-icon name="logo-pinterest"></ion-icon></li>
                                                </ul>
                                          </div>
                                    </div>
                              </div>
                        </footer>
                  </div>
            </div>

            <!-- FOOTER ENDS -->

      </div>

      <script type="text/javascript">

      //Scroll reveal animations

      new WOW().init();

      //Scroll activated background change
      $(function() {
            $(document).scroll(function() {
                  var $nav = $(".nav");
                  $nav.toggleClass('scrolled', $(this).scrollTop() > $nav.height());
            });
      });

      //Toggle MENU

      var t1 = new TimelineMax({paused: true});
      t1.to(".menu", 0.5, {
            left: "0%",
            ease: Power2.easeInOut
      });

      t1.reverse();
      $(document).on("click", ".menu-open", function() {
            t1.reversed(!t1.reversed());
      });
      $(document).on("click", ".menu-close", function() {
            t1.reversed(!t1.reversed());
      });

      </script>
</body>
</html>








CONTACT PAGE CODE


<!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <meta name="author" content="Belzarion - franguardado28@gmail.com">
      <link rel="icon" href="yourIconUrl" type="image/gif" sizes="16x16">
      <title>Contact - The Zurfaro</title>

      <!-- external stylesheet -->
      <link rel="stylesheet" href="style.css">

      <!-- bootstrapcdn -->
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

      <!-- icon pack -->
      <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>

      <!-- google font -->
      <link href="https://fonts.googleapis.com/css?family=Playfair+Display&display=swap" rel="stylesheet">

      <!-- jquery cdn -->
      <script src="https://code.jquery.com/jquery-3.4.1.js"></script>

      <!-- tweenmax (greensock) cdn -->
      <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.2/TweenMax.min.js"></script>

      <!-- for on scroll animations -->
      <link rel="stylesheet" href="animate.css">
      <script src="wow.min.js"></script>
</head>
<body>
      <div class="contact-container">

            <!-- NAVIGATION STARTS -->

            <div class="nav">
                  <div class="menu-open">
                        <ion-icon name="menu"></ion-icon>
                  </div>
                  <div class="brand">
                        <span><a href="index.html">The Zurfaro</a></span>
                  </div>
                  <div class="cart">
                        <ion-icon name="cart"></ion-icon>
                  </div>
                  <div class="menu">
                        <div class="menu-close">
                              <ion-icon name="close"></ion-icon>
                        </div>
                        <ul>
                              <li><a href="index.html">Home</a></li>
                              <li><a href="shop.html">Collection</a></li>
                              <li><a href="product.html">Product</a></li>
                              <li><a href="about.html">Our story</a></li>
                              <li><a href="contact.html">Contact</a></li>
                        </ul>
                        <div class="media-menu">
                              <ul>
                                    <li><ion-icon name="logo-facebook"></ion-icon></li>
                                    <li><ion-icon name="logo-instagram"></ion-icon></li>
                                    <li><ion-icon name="logo-twitter"></ion-icon></li>
                                    <li><ion-icon name="logo-pinterest"></ion-icon></li>
                              </ul>
                        </div>
                  </div>
            </div>

            <!-- NAVIGATION ENDS -->

            <!-- DATA SECTION STARS -->

            <div class="about-hero">
                  <div class="container-fluid hero wow fadeInUp">
                        <h1 id="hero-title">Contact Me</h1>
                  </div>

                  <div class="container content">
                        <p class="wow fadeInUp">What are you waiting for? time is always right. The place does not matter, the time does not matter, you have what you need right now and better thingd will come along.</p>

                        <form>
                              <div class="form-group">
                                    <label>Name</label>
                                    <input type="text" class="form-control wow fadeInUp" data-wow-delay="0.5s">
                              </div>

                              <div class="form-group">
                                    <label>E-MAIL</label>
                                    <input type="email" class="form-control wow fadeInUp" data-wow-delay="0.7s">
                              </div>

                              <div class="form-group">
                                    <label>MESSAGE</label>
                                    <textarea rows="3" class="form-control wow fadeInUp" data-wow-delay="0.8s"></textarea>
                              </div>

                              <div class="add-prod wow fadeInUp" data-wow-delay="0.2s">
                                    <a href="#">SUBMIT</a>
                              </div>
                        </form>

                  </div>
            </div>

            <!-- DATA SECTION ENDS -->

            <!-- FOOTER STARTS -->

            <div class="container-fluid footer">
                  <div class="section container">
                        <footer>
                              <div class="row">
                                    <div class="col-lg-3 block">
                                          <p>The Zurfaro, 250 Rutherford,
                                          <br>
                                          Boston,Massachusetts. 02129,
                                          <br>
                                          USA</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <p>CORP
                                          <br>
                                          Return Policy
                                          <br>
                                          Shipping</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <p>Careers
                                          <br>
                                          Community
                                          <br>
                                          Wholesale</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <div class="media">
                                                <ul>
                                                      <li><ion-icon name="logo-facebook"></ion-icon></li>
                                                      <li><ion-icon name="logo-instagram"></ion-icon></li>
                                                      <li><ion-icon name="logo-twitter"></ion-icon></li>
                                                      <li><ion-icon name="logo-pinterest"></ion-icon></li>
                                                </ul>
                                          </div>
                                    </div>
                              </div>
                        </footer>
                  </div>
            </div>

            <!-- FOOTER ENDS -->
            </div>

            <script type="text/javascript">

            //Scroll reveal animations

            new WOW().init();

            //Scroll activated background change
            $(function() {
                  $(document).scroll(function() {
                        var $nav = $(".nav");
                        $nav.toggleClass('scrolled', $(this).scrollTop() > $nav.height());
                  });
            });

            //Toggle MENU

            var t1 = new TimelineMax({paused: true});
            t1.to(".menu", 0.5, {
                  left: "0%",
                  ease: Power2.easeInOut
            });

            t1.reverse();
            $(document).on("click", ".menu-open", function() {
                  t1.reversed(!t1.reversed());
            });
            $(document).on("click", ".menu-close", function() {
                  t1.reversed(!t1.reversed());
            });

            </script>
</body>
</html>









SHOP CONTENT CODE

<!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <meta name="author" content="Belzarion - franguardado28@gmail.com">
      <link rel="icon" href="yourIconUrl" type="image/gif" sizes="16x16">
      <title>Collection - The Zurfaro</title>

      <!-- external stylesheet -->
      <link rel="stylesheet" href="style.css">

      <!-- bootstrapcdn -->
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

      <!-- icon pack -->
      <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>

      <!-- google font -->
      <link href="https://fonts.googleapis.com/css?family=Playfair+Display&display=swap" rel="stylesheet">

      <!-- jquery cdn -->
      <script src="https://code.jquery.com/jquery-3.4.1.js"></script>

      <!-- tweenmax (greensock) cdn -->
      <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.2/TweenMax.min.js"></script>

      <!-- for on scroll animations -->
      <link rel="stylesheet" href="animate.css">
      <script src="wow.min.js"></script>
</head>
<body>
      <div class="shop-container">

            <!-- NAVIGATION STARTS -->

            <div class="nav">
                  <div class="menu-open">
                        <ion-icon name="menu"></ion-icon>
                  </div>
                  <div class="brand">
                        <span><a href="index.html">The Zurfaro</a></span>
                  </div>
                  <div class="cart">
                        <ion-icon name="cart"></ion-icon>
                  </div>
                  <div class="menu">
                        <div class="menu-close">
                              <ion-icon name="close"></ion-icon>
                        </div>
                        <ul>
                              <li><a href="index.html">Home</a></li>
                              <li><a href="shop.html">collection</a></li>
                              <li><a href="product.html">Product</a></li>
                              <li><a href="about.html">My story</a></li>
                              <li><a href="contact.html">Contact</a></li>
                        </ul>
                        <div class="media-menu">
                              <ul>
                                    <li><ion-icon name="logo-facebook"></ion-icon></li>
                                    <li><ion-icon name="logo-instagram"></ion-icon></li>
                                    <li><ion-icon name="logo-twitter"></ion-icon></li>
                                    <li><ion-icon name="logo-pinterest"></ion-icon></li>
                              </ul>
                        </div>
                  </div>
            </div>

            <!-- NAVIGATION ENDS -->

            <div class="whitespaces"></div>

            <!-- COLLECTION STARTS -->

            <div class="collection">
                  <p id="heading">Best sellers</p>

                  <div class="section prod-list">
                        <div class="container-fluid">
                              <div class="row some-cards">
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.5s">
                                          <a href="product.html">
                                                <p id="price"> VALERIE USD $70.00</p>
                                                <img src="images/prod-04.jpg" alt="">
                                                <p id="prod-desc">Day-to-day service 2019 acquisition in Green</p>
                                          </a>
                                    </div>
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.8s">
                                          <a href="product.html">
                                                <p id="price">DEVON USD $50.00</p>
                                                <img src="images/prod-05.jpg" alt="">
                                                <p id="prod-desc">Day-to-day service 2019/2020 in Crimson</p>
                                          </a>
                                    </div>
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="1.1s">
                                          <a href="product.html">
                                                <p id="price">GRIFFIN USD $50.00</p>
                                                <img src="images/prod-06.jpg" alt="">
                                                <p id="prod-desc">Day-to-day 2019 in Marron</p>
                                          </a>
                                    </div>
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="1.4s">
                                          <a href="product.html">
                                                <p id="price">LUKE USD $75.00</p>
                                                <img src="images/prod-07.jpg" alt="">
                                                <p id="prod-desc">Day-to-day service 2019 in Obscure MIB</p>
                                          </a>
                                    </div>
                              </div>
                        </div>
                  </div>
            </div>

            <!-- COLLECTION ENDS -->

            <!-- BANNER SECTION STARTS -->

            <div class="row prod-sec">
                  <div class="col-lg-6 prod-img">
                        <img src="images/single-prod.jpg" alt="">
                  </div>

                  <div class="col-lg-4 prod-desc">
                        <br><br>
                        <p class="wow fadeInUp" data-wow-delay="0.5s">More doing and less talking is more useful. There is no tomorrow only the today and the now.</p>

                        <div class="link wow fadeInUp" data-wow-delay="0.6s">
                              <a href="shop.html">Go shopping <ion-icon name="arrow-round-forward"></ion-icon></a>
                        </div>
                  </div>
            </div>

            <!-- THIS IS BANNER SECTION ENDS -->

            <!-- COLLECTION AND ACQUISITION STARTS -->

            <div class="collection">
                  <p id="heading">Latest acquisition</p>

                  <div class="section prod-list">
                        <div class="container-fluid">
                              <div class="row some-cards">
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.5s">
                                          <a href="product.html">
                                                <p id="price">          Valerie USD $70.00</p>
                                                <img src="images/prod-04.jpg" alt="">
                                                <p id="prod-desc">Day-to-say service 2019 in Green</p>
                                          </a>
                                    </div>
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.8s">
                                          <a href="product.html">
                                                <p id="price">          Devon USD $80.00</p>
                                                <img src="images/prod-05.jpg" alt="">
                                                <p id="prod-desc">Day-to-day service 2019/2020 in Dark Blue</p>
                                          </a>
                                    </div>
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="1.1s">
                                          <a href="product.html">
                                                <p id="price">          Griffin USD $20.00</p>
                                                <img src="images/prod-06.jpg" alt="">
                                                <p id="prod-desc">Day-to-day service 2019 in Beige</p>
                                          </a>
                                    </div>
                                    <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="1.4s">
                                          <a href="product.html">
                                                <p id="price">          Luke USD $25.00</p>
                                                <img src="images/prod-07.jpg" alt="">
                                                <p id="prod-desc">Day-to-day service 2019 in Cocoa Brown</p>
                                          </a>
                                    </div>
                              </div>
                        </div>
                  </div>
            </div>

            <!-- COLLECTION ENDS -->

            <!-- CATEGORIES SECTION STARTS -->

            <div class="container-fluid">
                  <div class="row section shop">
                        <div class="col-lg-8">
                              <p class="wow fadeInUp" data-wow-delay="0.4s">What are you waiting for? time is always right. The place does not matter, the time does not matter, you have what you need right now and better thingd will come along.</p>

                              <div class="link wow fadeInUp" data-wow-delay="0.6s">
                                    <a href="shop.html">Get more <ion-icon name="arrow-round-forward"></ion-icon></a>
                              </div>
                        </div>
                  </div>

                  <div class="container-fluid">
                        <div class="row some-cards">
                              <div class="col-lg-3"></div>

                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.3s">
                                    <img src="images/prod-01.jpg" alt="">
                                    <p id="prod-desc">Belzarion is a Youtube channel that started in 2019 with the purpose to entertain gamers!</p>
                              </div>

                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.5s">
                                    <img src="images/prod-02.jpg" alt="">
                                    <p id="prod-desc">The Zurfaro, is a station that represents being smart and creative. This channel is specifically made to educate web development and UI/UX!</p>
                              </div>

                              <div class="col-lg-3 prod wow fadeInUp" data-wow-delay="0.7s">
                                    <img src="images/prod-03.jpg" alt="">
                                    <p id="prod-desc">Combine Belzarion and The Zurfaro, what you get is the right combination to never get bored!</p>
                              </div>
                        </div>
                  </div>
            </div>


            <!-- CATEGORIES SECTION ENDS -->

            <div class="whitespaces"></div>

            <!-- FOOTER STARTS -->

            <div class="container-fluid footer">
                  <div class="section container">
                        <footer>
                              <div class="row">
                                    <div class="col-lg-3 block">
                                          <p>The Zurfaro, 250 Rutherford,
                                          <br>
                                          Boston, Massachusetts, 02129,
                                          <br>
                                          USA</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <p>Corp
                                          <br>
                                          Return Policy
                                          <br>
                                          Shipping</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <p>Careers
                                          <br>
                                          Community
                                          <br>
                                          Wholesale</p>
                                    </div>
                                    <div class="col-lg-3 block">
                                          <div class="media">
                                                <ul>
                                                      <li><ion-icon name="logo-facebook"></ion-icon></li>
                                                      <li><ion-icon name="logo-instagram"></ion-icon></li>
                                                      <li><ion-icon name="logo-twitter"></ion-icon></li>
                                                      <li><ion-icon name="logo-pinterest"></ion-icon></li>
                                                </ul>
                                          </div>
                                    </div>
                              </div>
                        </footer>
                  </div>
            </div>

            <!-- FOOTER ENDS -->

      </div>
      <script type="text/javascript">

      //Scroll reveal animations

      new WOW().init();

      //Scroll activated background change
      $(function() {
            $(document).scroll(function() {
                  var $nav = $(".nav");
                  $nav.toggleClass('scrolled', $(this).scrollTop() > $nav.height());
            });
      });

      //Toggle MENU

      var t1 = new TimelineMax({paused: true});
      t1.to(".menu", 0.5, {
            left: "0%",
            ease: Power2.easeInOut
      });

      t1.reverse();
      $(document).on("click", ".menu-open", function() {
            t1.reversed(!t1.reversed());
      });
      $(document).on("click", ".menu-close", function() {
            t1.reversed(!t1.reversed());
      });


      </script>
</body>
</html>






