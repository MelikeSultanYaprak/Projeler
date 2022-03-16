# Projeler
Html/Css
<!DOCTYPE html>
<html lang="tr">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>UYGULAMA-RELATİVE-ABSOLUTE</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@1,300&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@1,300&family=The+Nautigal&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="buttons.css" />
    <style>
      .box {
        /*kfont-family: "Be Vietnam Pro", sans-serif;*/
        display: inline-block;
        width: 400px;
        height: 200px;
        text-align: center;
        color: darkmagenta;
      }
      .box p {
        /*font-family: "Be Vietnam Pro", sans-serif; */
        text-align: center;
        color: darkslategrey;
        padding: 0px 20px;
      }
      .box h3 {
        text-align: center;
      }

      * {
        box-sizing: border-box;
        font-weight: lighter;
        font-family: fantasy;
      }
      body {
        margin: 0%;
      }

      .main-header {
        background-color: rgba(34, 140, 240, 0.295);
        height: 60px;
      }

      .main-nav {
        text-align: right;
        width: calc(100% - 101px);
        display: inline-block;
      }

      #showcase {
        position: relative;
        background-image: url("gul.jpg");
        background-position: bottom;
        background-size: 100%;

        height: 600px;

        padding: 10px;
      }
      #how-it-works {
        padding: 20px 20px;
        text-align: center;
      }
      #how-it-works-div p {
        color: darkturquoise;
        font-weight: bold;
        padding: 0px 100px;
        margin-bottom: 50px;
      }
      h1 {
        /*border: 5px solid black;*/
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: beige;
        font-size: xx-large;
        margin: 0%;
      }

      ul {
        margin: 0%;
      }
      .main-nav__item {
        display: inline-block;
        padding: 3px 0px 4px 6px;
      }

      .box i {
        color: mediumblue;
      }
      .box2 {
        display: inline-block;
        width: 749px;
        height: 300px;
        padding: 0px 0px;
      }
      #january {
        background-color: aqua;
        background-image: url("cicek-tavsan.jpg");
        background-size: 100%;

        background-position: bottom;
      }
      #february {
        background-color: rgb(201, 255, 115);
        width: 50%;
        vertical-align: top;
        padding: 40px;

        font-size: 20px;
      }
      #february h3 {
        color: rgb(20, 255, 247);
      }
      #february p {
        color: rgb(150, 236, 12);
      }

      .section-title {
        text-align: center;
        margin-top: 35px;
        margin-bottom: 40px;
      }
      .plan {
        background-color: white;
        text-align: center;
        padding: 16px;

        width: 33.3%;
        float: left;
      }
      .recommended-plan {
        background: rgb(201, 255, 115) !important;
        color: blue;
      }
      .plan__badge {
        padding: 8px;
        border-radius: 5px;
        background-color: rgb(89, 250, 250);
      }
      .inner-plan {
        background-color: rgb(89, 250, 250);
        padding: 25px 10px;
        border-radius: 6px;
        box-shadow: rgb(38, 57, 77) 10px 20px 30px -10px;
        transition: box-shadow 0.4s;
      }
      .inner-plan:hover {
        box-shadow: rgb(38, 57, 77, 0.5) 10px 20px 30px -10px;
      }
      .plan__features {
        list-style: none;
        margin: 0px;
        padding: 0px;
      }
      .plan__features li {
        margin: 6px 0px;
      }
      .clearfix {
        content: "";
        display: block;
        clear: both;
      }

      .container {
        margin: 0 auto;
        width: 1000px;
      }
      .recommended-plan {
        position: relative;
        top: -20px;
      }
      .inner-plan-1,
      .inner-plan-2 {
        background-color: aquamarine;
        padding: 15px;
        border: 0px;
        border-radius: 5px;
      }
      .inner-plan-1:hover,
      .inner-plan-2:hover {
        box-shadow: rgb(38, 57, 77) 10px 20px 30px -10px;
        transition: box-shadow 0.4s;
      }
      .btn {
        color: black;
        background-color: rgba(34, 140, 240, 0.479);
      }
      .btn:hover {
        color: black;
        background-color: bisque;
      }
    </style>
  </head>

  <body>
    <header class="main-header">
      <a class="btn btn-outline-primary" href="#" class="main-header__logo">MovieApp</a>
      <nav class="main-nav">
        <ul class="main-nav__items">
          <li class="main-nav__item">
            <a class="btn btn-outline-primary" href="#">Filmler</a>
          </li>
          <li class="main-nav__item">
            <a class="btn btn-outline-primary" href="#">Diziler</a>
          </li>
          <li class="main-nav__item main-nav__item--login">
            <a class="btn btn-outline-primary" href="#">Login</a>
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="showcase">
        <h1>Welcome to MovieApp</h1>
      </section>

      <section id="how-it-works">
        <div id="how-it-works-div">
          <h2>How it works?</h2>
          <p>
            Kursumuzdaki konu başlıkları sırasıyla; Html, Css, Sass & Scss,
            Flexbox, Javascript, Angular, Bootstrap, JQuery ve Asp.Net Core Mvc
            konu başlıklarıdır.
          </p>
        </div>

        <div id="container">
          <div class="box" id="first">
            <i class="fas fa-american-sign-language-interpreting fa-2x"></i>
            <h3>Register</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Blanditiis perferendis ullam animi modi itaque vero!
            </p>
          </div>
          <div class="box" id="second">
            <i class="fab fa-buffer fa-2x"></i>
            <h3>Choose a Plan</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Blanditiis perferendis ullam animi modi itaque vero!
            </p>
          </div>
          <div class="box" id="thirty">
            <i class="fas fa-sign-out-alt fa-2x"></i>
            <h3>Enjoy Movify</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Blanditiis perferendis ullam animi modi itaque vero!
            </p>
          </div>
        </div>
      </section>
      <section id="features">
        <div id="looking">
          <div class="box2" id="january"></div>
          <div class="box2" id="february">
            <h3>Hi,My name is Melike.</h3>
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quidem
              dolore nihil sunt aliquam quisquam amet quam laudantium vitae
              architecto quasi, delectus nostrum placeat voluptate
              necessitatibus ad animi dolorem ullam incidunt!
            </p>
            <a class="btn btn-secondary" href="#">View Features</a>
          </div>
        </div>
        <section id="plans">
          <div class="row">
            <h2 class="section-title">Become a Premium Member</h2>
            <div class="container clearfix">
              <div class="plan">
                <div class="inner-plan-1">
                  <h2>Free</h2>
                  <h3>0/month</h3>
                  <ul class="plan__features">
                    <li>Melike</li>
                    <li>Sultan</li>
                    <li>Yaprak</li>
                    <li>Miraç</li>
                    <li>Yaprak</li>
                  </ul>
                  <div>
                    <button class="btn btn-primary">Choose Plan</button>
                  </div>
                </div>
              </div>
              <div class="plan">
                <div class="inner-plan recommended-plan">
                  <h2 class="plan__badge">Recommended</h2>
                  <h2>Basic</h2>
                  <h3>$19.99/month</h3>
                  <ul class="plan__features">
                    <li>Melike</li>
                    <li>Sultan</li>
                    <li>Yaprak</li>
                    <li>Miraç</li>
                    <li>Yaprak</li>
                  </ul>
                  <div>
                    <button class="btn btn-primary">Choose Plan</button>
                  </div>
                </div>
              </div>
              <div class="plan">
                <div class="inner-plan-2">
                  <h2>Premium</h2>
                  <h3>$19.99/month</h3>
                  <ul class="plan__features">
                    <li>Melike</li>
                    <li>Sultan</li>
                    <li>Yaprak</li>
                    <li>Miraç</li>
                    <li>Yaprak</li>
                  </ul>
                  <div>
                    <button class="btn btn-primary">Choose Plan</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </section>
    </main>
  </body>
</html>
