<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/2.0.0/modern-normalize.min.css"
      integrity="sha512-4xo8blKMVCiXpTaLzQSLSw3KFOVPWhm/TRtuPVc4WG6kUgjH6J03IBuG7JZPkcWMxJ5huwaBpOpnwYElP/m6wg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="./css/styles.css" />
    <title>Homework3</title>
  </head>
  <body>
    <header class="page-header">
      <div class="header__container container">
        <nav class="header__nav">
          <a href="./index.html" class="nav-logo"
            >Web<span class="logo-span">Studio</span></a
          >
          <ul class="nav-list">
            <li class="nav-list__list-item">
              <a class="link" href="./index.html">Studio</a>
            </li>
            <li class="nav-list__list-item">
              <a class="link" href="">Portfolio</a>
            </li>
            <li class="nav-list__list-item">
              <a class="link" href="">Contacts</a>
            </li>
          </ul>
        </nav>
        <address id="contact" class="contact">
          <ul class="contact-list">
            <li class="contact-list__list-item">
              <a class="link" href="mailto:info@devstudio.com"
                >info@devstudio.com</a
              >
            </li>
            <li class="contact-list__list-item">
              <a class="link" href="tel:+110001111111">+11 (000) 111-11-11</a>
            </li>
          </ul>
        </address>
      </div>
    </header>
    <main>
      <section class="first-section" id="hero">
        <div class="container">
          <h1 class="first-section__title">
            Effective Solutions for Your Business
          </h1>
          <button class="first-section__btn" type="button">
            Order Service
          </button>
        </div>
      </section>
      <section class="second-section">
        <div class="container">
          <h2 class="visually-hidden">RandomTitle</h2>
          <ul class="second-section__list">
            <li class="second-section__list-item">
              <h3 class="second-section__list-title">Strategy</h3>
              <p class="text">
                Our goal is to identify the business problem to walk away with
                the perfect and creative solution.
              </p>
            </li>
            <li class="second-section__list-item">
              <h3 class="second-section__list-title">Punctuality</h3>
              <p class="text">
                Bring the key message to the brand's audience for the best price
                within the shortest possible time.
              </p>
            </li>
            <li class="second-section__list-item">
              <h3 class="second-section__list-title">Diligence</h3>
              <p class="text">
                Research and confirm brands that present the strongest digital
                growth opportunities and minimize risk.
              </p>
            </li>
            <li class="second-section__list-item">
              <h3 class="second-section__list-title">Technologies</h3>
              <p class="text">
                Design practice focused on digital experiences. We bring forth a
                deep passion for problem-solving.
              </p>
            </li>
          </ul>
        </div>
      </section>
      <section class="third-section" id="team">
        <div class="container">
          <h2 class="third-section__title">Our Team</h2>
          <ul class="third-section__list">
            <li class="list-item">
              <img src="./images/img1.jpg" alt="Mark Guerrero" width="264" />
              <div class="list-item__container">
                <h3 class="member-name">Mark Guerrero</h3>
                <p class="text">Product Designer</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/img2.jpg" alt="Tom Ford" width="264" />
              <div class="list-item__container">
                <h3 class="member-name">Tom Ford</h3>
                <p class="text">Frontend Developer</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/img3.jpg" alt="Camila Garcia" width="264" />
              <div class="list-item__container">
                <h3 class="member-name">Camila Garcia</h3>
                <p class="text">Marketing</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/img4.jpg" alt="Daniel Wilson" width="264" />
              <div class="list-item__container">
                <h3 class="member-name">Daniel Wilson</h3>
                <p class="text">UI Designer</p>
              </div>
            </li>
          </ul>
        </div>
      </section>
      <section class="forth-section" id="portfolio">
        <div class="container">
          <h2 class="forth-section__title">Our Portfolio</h2>
          <ul class="forth-section__list">
            <li class="list-item">
              <img src="./images/portfolio1.jpg" alt="portfolio1" width="360" />
              <div class="forth-section_list-item-container">
                <h3 class="list-item__title">Banking App</h3>
                <p class="text">App</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/portfolio2.jpg" alt="portfolio2" width="360" />
              <div class="forth-section_list-item-container">
                <h3 class="list-item__title">Cashless Payment</h3>
                <p class="text">Marketing</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/portfolio3.jpg" alt="portfolio3" width="360" />
              <div class="forth-section_list-item-container">
                <h3 class="list-item__title">Meditation App</h3>
                <p class="text">App</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/portfolio4.jpg" alt="portfolio4" width="360" />
              <div class="forth-section_list-item-container">
                <h3 class="list-item__title">Taxi Service</h3>
                <p class="text">Marketing</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/portfolio5.jpg" alt="portfolio5" width="360" />
              <div class="forth-section_list-item-container">
                <h3 class="list-item__title">Screen Illustrations</h3>
                <p class="text">Design</p>
              </div>
            </li>
            <li class="list-item">
              <img src="./images/portfolio6.jpg" alt="portfolio6" width="360" />
              <div class="forth-section_list-item-container">
                <h3 class="list-item__title">Online Courses</h3>
                <p class="text">Marketing</p>
              </div>
            </li>
          </ul>
        </div>
      </section>
    </main>
    <footer class="footer">
      <div class="container">
        <a class="footer-logo" href="./index.html"
          >Web<span class="logo-span">Studio</span></a
        >
        <p class="text">
          Increase the flow of customers and sales for your business with
          digital marketing & growth solutions.
        </p>
      </div>
    </footer>
  </body>
</html>
