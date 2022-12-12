<!DOCTYPE html>
<html lang="pl">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My project</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <nav class="heads site-nav">
      <div class="container wrapper">
        <!--child 1-->
        <a class="logo-font" href="index.html">Web<span class="span-head">Studio</span></a>

        <ul class="ul-info ul-info-links">
          <li class="link-list"><a class="menu" href="#">Agencja</a></li>
          <li class="link-list"><a class="menu" href="portfolio.html">Portfolio</a></li>
          <li class="link-list"><a class="menu" href="#">Kontakt</a></li>
        </ul>
        <!--child 2-->
        <div class="contact">
          <a class="contact-links" href="mailto:info@devstudio.com">
            <svg class="contact-icon" width="16" height="12">
              <use href="images/icons.svg#icon-envelope"></use>
            </svg>
            info@devstudio.com</a
          >

          <a class="contact-links" href="tel:+48111111111">
            <svg class="contact-icon" width="16" height="12">
              <use href="images/icons.svg#icon-smartphone"></use>
            </svg>
            +48 111 111 111</a
          >
        </div>
      </div>
    </nav>
    <main>
      <section class="section-info hero-bg section">
        <div class="container section-info-wrapper">
          <h1 class="headline-one">EFEKTYWNE ROZWIĄZANIA<br />DLA WASZEGO BIZNESU</h1>
          <button class="button-click" type="button">Zamów usługę</button>
        </div>
      </section>

      <section class="section">
        <div class="container">
          <article class="article-info">
            <ul class="ul-info lorem-section">
              <li class="li-no-list">
                <div class="lorem-icon">
                  <svg class="atuts-icon" width="65.32" height="70"><use href=./images/icons.svg#icon-antenna-1></use></svg>
                </div>
                <h2 class="headline-two">LOREM IPSUM</h2>
                <p class="list-style">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam vel arcu sem. Sed non
                  sodales dui. Interdum et malesuada
                </p>
              </li>

              <li class="li-no-list">
                <div class="lorem-icon2">
                  <svg class="atuts-icon" width="66.96" height="70"><use href=./images/icons.svg#icon-clock-1></use></svg>
                </div>
                <h2 class="headline-two">LOREM IPSUM</h2>
                <p class="list-style">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam vel arcu sem. Sed non
                  sodales dui. Interdum et malesuada
                </p>
              </li>

              <li class="li-no-list">
                <div class="lorem-icon3">
                  <svg class="atuts-icon" width="70" height="53.69"><use href=./images/icons.svg#icon-diagram-1></use></svg>
                </div>
                <h2 class="headline-two">LOREM IPSUM</h2>
                <p class="list-style">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam vel arcu sem. Sed non
                  sodales dui. Interdum et malesuada
                </p>
              </li>

              <li class="li-no-list">
                <div class="lorem-icon4">
                  <svg class="atuts-icon" width="54.83" height="60.66"><use href=./images/icons.svg#icon-astronaut-1></use></svg>
                </div>
                <h2 class="headline-two">LOREM IPSUM</h2>
                <p class="list-style">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam vel arcu sem. Sed non
                  sodales dui. Interdum et malesuada
                </p>
              </li>
            </ul>
          </article>
        </div>
      </section>

      <section class="section">
        <div class="container">
          <article>
            <h2 class="titles">Czym się zajmujemy</h2>
            <ul class="ul-info pictures">
              <li class="li-no-list ">
                <img
                  src="images/services/keyboardWork.jpg"
                  alt="Praca na klawiaturze"
                  width="370"
                  height="294"
                />
              </li>

              <li class="li-no-list">
                <img
                  src="images/services/cellphoneWork.jpg"
                  alt="Opracowywanie aplikacji na smartfon"
                  width="370"
                  height="294"
                />
              </li>

              <li class="li-no-list ">
                <img
                  src="images/services/tabletWork.jpg"
                  alt="Tworzenie wyglądu strony"
                  width="370"
                  height="294"
                />
              </li>
            </ul>
          </article>
        </div>
      </section>

      <section class="titles-team section">
        <div class="container">
          <h2 class="our-team">Nasz zespół</h2>

          <ul class="ul-info pictures">
            <li class="no-list">
              <figure class="box-shadow">
                <img src="images/employees/itMan.jpg" alt="John Doe" width="270" height="260" />
                <figcaption class="team">
                  <p><span class="johndoe">John Doe</span></p>
                  <div class="position">Product Designer</div>
                </figcaption>
              </figure>      
              <div class="social-icons">
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-instagram-2" > </use>
                  </svg>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-twitter-1" > </use>
                  </svg>
                </a>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-facebook-1" > </use>
                  </svg>
                </a>   
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-linkedin-1" > </use>
                  </svg>
                </a>
          </div>               
            </li>
            
            <li class="no-list">
              <figure class="box-shadow">
                <img
                  src="images/employees/smiligWoman.jpg"
                  alt="John Doe"
                  width="270"
                  height="260"
                />
                <figcaption class="team">
                  <p><span class="johndoe">John Doe</span></p>
                  <div class="position">Frontend Developer</div>
                </figcaption>
              </figure>
              <div class="social-icons">
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-instagram-2" > </use>
                  </svg>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-twitter-1" > </use>
                  </svg>
                </a>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-facebook-1" > </use>
                  </svg>
                </a>   
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-linkedin-1" > </use>
                  </svg>
                </a>
          </div>              
            </li>

            <li class="no-list">
              <figure class="box-shadow">
                <img
                  src="images/employees/manInWhite.jpg"
                  alt="John Doe"
                  width="270"
                  height="260"
                />
                <figcaption class="team">
                  <p><span class="johndoe">John Doe</span></p>
                  <div class="position">Marketing</div>
                </figcaption>
              </figure>
              <div class="social-icons">
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-instagram-2" > </use>
                  </svg>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-twitter-1" > </use>
                  </svg>
                </a>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-facebook-1" > </use>
                  </svg>
                </a>   
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-linkedin-1" > </use>
                  </svg>
                </a>
          </div>               
            </li>

            <li class="no-list">
              <figure class="box-shadow">
                <img
                  src="images/employees/smilingMan.jpg"
                  alt="John Doe"
                  width="270"
                  height="260"
                />
                <figcaption class="team">
                  <p><span class="johndoe">John Doe</span></p>
                  <div class="position">UI Designer</div>
                </figcaption>
              </figure>
              <div class="social-icons">
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-instagram-2" > </use>
                  </svg>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-twitter-1" > </use>
                  </svg>
                </a>
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-facebook-1" > </use>
                  </svg>
                </a>   
                <a class="sm-circle" href="#">
                  <svg width="20px" height="20px" class="sm-icons">
                    <use href="./images/icons.svg#icon-linkedin-1" > </use>
                  </svg>
                </a>
          </div>        
            </li>
          </ul>
        </div>
      </section>
      <section class="section our-customers">
        <div class="container">
            <h2>Nasi klienci</h2>
            <ul class="our-customers-list">
                <li class="our-customers-bg">
                    <svg class="icon-customers" width="106" height="60.04">
                        <use href="./images/icons.svg#icon-client1"></use>
                    </svg>
                </li>

                <li class="our-customers-bg">
                    <svg class="icon-customers" width="106" height="60.04">
                        <use href="./images/icons.svg#icon-client2"></use>
                    </svg>
                </li>

                <li class="our-customers-bg">
                    <svg class="icon-customers" width="106" height="60">
                        <use href="./images/icons.svg#icon-client3"></use>
                    </svg>
                </li>

                <li class="our-customers-bg">
                    <svg class="icon-customers" width="106" height="60">
                        <use href="./images/icons.svg#icon-client4"></use>
                    </svg>
                </li>

                <li class="our-customers-bg">
                    <svg class="icon-customers" width="106" height="60">
                        <use href="./images/icons.svg#icon-client5"></use>
                    </svg>
                </li>

                <li class="our-customers-bg">
                    <svg class="icon-customers" width="106" height="60">
                     <use href="./images/icons.svg#icon-client6"></use>
                    </svg>
                </li>
            </ul> 
        </div>
    </section>
    </main>
    <footer class="footer-info">
      <div class="container">
        <a class="footer-logo" href="index.html">Web<span class="span-footer">Studio</span></a>
        <address class="address-info">
          <div class="city-street">m.Warszawa, Aleje Jerozolimskie 21</div>
          <div class="contact-div">
            <a class="contact-info" href="mailto:info@example.com">info@example.com</a>
            <a class="contact-info" href="tel:+48111111111">+48 111 111 111</a>
          </div>
        </address>
      </div>
    </footer>
  </body>
</html>
