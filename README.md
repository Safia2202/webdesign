# ONE page website
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <link rel="shortcut icon" type="image/png" href="img/icon.png" />

    <link
      href="https://fonts.googleapis.com/css?family=Poppins:300,400,500,600&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
    <title> Web design</title>

    <script defer src="script.js"></script>
  </head>
  <body>
    <header class="header">
      <nav class="nav">
        <div
      
          class="nav__logo"
          id="logo"> Logo here
          
        </div>
        <ul class="nav__links">
          <li class="nav__item">
            <a class="nav__link" href="#section--1">Features</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#section--2">Operations</a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#section--3">Testimonials</a>
          </li>
          <li class="nav__item">
            <a class="nav__link nav__link--btn btn--show-modal" href="#"
              >Open account</a
            >
          </li>
        </ul>
      </nav>

      <div class="header__title">
        <!-- <h1 onclick="alert('HTML alert')"> -->
        <h1>
          When
          <!-- Green highlight effect -->
          <span class="highlight">need <br />
          <span class="highlight">Web design</span>
        </h1>
        <h4>Our services</h4>
        <button class="btn--text btn--scroll-to">Learn more &DownArrow;</button>
        <img
          src="img/hero.png"
          class="header__img"
          alt="Minimalist bank items"
        />
      </div>
    </header>

    <section class="section" id="section--1">
      <div class="section__title">
        <h2 class="section__description">Features</h2>
        <h3 class="section__header">Make your web become more atractive.</h3>
      </div>

      <div class="features">
        <img
          src="img/digital-lazy.jpg"
          data-src="img/digital.jpg"
          alt="Computer"
          class="features__img lazy-img"
        />
        <div class="features__feature">
          <div class="features__icon">
            <svg>
              <use xlink:href="img/icons.svg#icon-monitor"></use>
            </svg>
          </div>
          <h5 class="features__header">With out profestional service</h5>
          <p>Online marketing, Webdesign, bank...Call us.</p>
        </div>

        <div class="features__feature">
          <div class="features__icon">
            <svg>
              <use xlink:href="img/icons.svg#icon-trending-up"></use>
            </svg>
          </div>
          <h5 class="features__header">Watch your money grow</h5>
          <p>All you need is take a call, we will handle the rest</p>
        </div>
        <img
          src="img/grow-lazy.jpg"
          data-src="img/grow.jpg"
          alt="Plant"
          class="features__img lazy-img"
        />

        <img
          src="img/card-lazy.jpg"
          data-src="img/card.jpg"
          alt="Credit card"
          class="features__img lazy-img"
        />
        <div class="features__feature">
          <div class="features__icon">
            <svg>
              <use xlink:href="img/icons.svg#icon-credit-card"></use>
            </svg>
          </div>
          <h5 class="features__header">Free services included</h5>
          Free services like ... are included
          <p></p>
        </div>
      </div>
    </section>

    <section class="section" id="section--2">
      <div class="section__title">
        <h2 class="section__description">Operations</h2>
        <h3 class="section__header">
          Everything as simple as possible, but no simpler.
        </h3>
      </div>

      <div class="operations">
        <div class="operations__tab-container">
          <button
            class="btn operations__tab operations__tab--1 operations__tab--active"
            data-tab="1"
          >
            <span>01</span>Quick
          </button>
          <button class="btn operations__tab operations__tab--2" data-tab="2">
            <span>02</span> Flexible
          </button>
          <button class="btn operations__tab operations__tab--3" data-tab="3">
            <span>03</span>professional design
          </button>
        </div>
        <div
          class="operations__content operations__content--1 operations__content--active"
        >
          <div class="operations__icon operations__icon--1">
            <svg>
              <use xlink:href="img/icons.svg#icon-upload"></use>
            </svg>
          </div>
          <h5 class="operations__header">Try our services</h5>
          <p>Our services are :</p>
        </div>

        <div class="operations__content operations__content--2">
          <div class="operations__icon operations__icon--2">
            <svg>
              <use xlink:href="img/icons.svg#icon-home"></use>
            </svg>
          </div>
          <h5 class="operations__header">WEb design</h5>
          <p>Frontend</p>
        </div>
        <div class="operations__content operations__content--3">
          <div class="operations__icon operations__icon--3">
            <svg>
              <use xlink:href="img/icons.svg#icon-user-x"></use>
            </svg>
          </div>
          <h5 class="operations__header">Backend</h5>
          <p>Database related services</p>
        </div>
      </div>
    </section>

    <section class="section" id="section--3">
      <div class="section__title section__title--testimonials">
        <h2 class="section__description">Not sure yet?</h2>
        <h3 class="section__header">Try our service.</h3>
      </div>

      <div class="slider">
        <div class="slide">
          <div class="testimonial">
            <h5 class="testimonial__header">Best services ever!</h5>
            <blockquote class="testimonial__text">
              professional design
            </blockquote>
            <address class="testimonial__author">
              <img src="img/user-1.jpg" alt="" class="testimonial__photo" />
              <h6 class="testimonial__name">Safia</h6>
              <p class="testimonial__location">Tokyo, Japan</p>
            </address>
          </div>
        </div>

        <div class="slide">
          <div class="testimonial">
            <h5 class="testimonial__header">Try this!</h5>
            <blockquote class="testimonial__text">Our services</blockquote>
            <address class="testimonial__author">
              <img src="img/user-2.jpg" alt="" class="testimonial__photo" />
              <h6 class="testimonial__name">Olima</h6>
              <p class="testimonial__location">Osaka Japan</p>
            </address>
          </div>
        </div>

        <div class="slide">
          <div class="testimonial">
            <h5 class="testimonial__header">Modern design</h5>
            <blockquote class="testimonial__text">Modern design</blockquote>
            <address class="testimonial__author">
              <img src="img/user-3.jpg" alt="" class="testimonial__photo" />
              <h6 class="testimonial__name">Gomes</h6>
              <p class="testimonial__location">Lisbon, Portugal</p>
            </address>
          </div>
        </div>

        <button class="slider__btn slider__btn--left">&larr;</button>
        <button class="slider__btn slider__btn--right">&rarr;</button>
        <div class="dots"></div>
      </div>
    </section>

    <section class="section section--sign-up">
      <div class="section__title">
        <h3 class="section__header">
          The best day to join us was one year ago. The second best is today!
        </h3>
      </div>
      <button class="btn btn--show-modal">Contact now!</button>
    </section>

    <footer class="footer">
      <ul class="footer__nav">
        <li class="footer__item">
          <a class="footer__link" href="#">About</a>
        </li>
        <li class="footer__item">
          <a class="footer__link" href="#">Pricing</a>
        </li>
        <li class="footer__item">
          <a class="footer__link" href="#">Terms of Use</a>
        </li>
        <li class="footer__item">
          <a class="footer__link" href="#">Privacy Policy</a>
        </li>
        <li class="footer__item">
          <a class="footer__link" href="#">Careers</a>
        </li>
        <li class="footer__item">
          <a class="footer__link" href="#">Blog</a>
        </li>
        <li class="footer__item">
          <a class="footer__link" href="#">Contact Us</a>
        </li>
      </ul>
      <img src="# "alt="Logo" class="footer__logo" />
      <p class="footer__copyright">
        &copy; Copyright by
        <a class="footer__link twitter-link" target="_blank" href="#">Safia</a>
      </p>
    </footer>

    <div class="modal hidden">
      <button class="btn--close-modal">&times;</button>
      <h2 class="modal__header">
        Contact now <br />
        call <span class="highlight">mail</span>
      </h2>
      <form class="modal__form">
        <label>First Name</label>
        <input type="text" />
        <label>Last Name</label>
        <input type="text" />
        <label>Email Address</label>
        <input type="email" />
        <button class="btn">Next step &rarr;</button>
      </form>
    </div>
    <div class="overlay hidden"></div>

    <!-- <script src="script.js"></script> -->
  </body>
</html>
