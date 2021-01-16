<!DOCTYPE HTML>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <title>Fischer Fritz</title>
    <style>body {
  min-width: 1040px;
  margin: 0;
  padding: 0;
  font-size: 16px;
  line-height: 24px;
  font-family: "Arial", sans-serif;
  color: #404040;
  background-color: white;
}

.container {
  width: 1020px;
  margin: 0 auto;
}

.clearfix::after {
  content: "";
  display: table;
  clear: both;
}

.page-header {
  min-height: 490px;
  padding-top: 35px;
  background-image: url("shutterstock_332152151.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.page-header,
.page-footer {
  color: #c3c3c3;
  background-color: #363636;
}

.header-top {
  margin-bottom: 125px;
}

.header-logo {
  float: left;
  width: 150px;
  height: 150px;
}

.header-logo img {
  width: 150px;
  height: 150px;
}

.main-nav {
  float: left;
  width: 520px;
  margin: 0;
  margin-top: 18px;
  margin-left: 125px;
  padding: 0;
  list-style: none;
}

.main-nav li {
  float: left;
  margin-right: 50px;
  text-transform: uppercase;
}

.main-nav li:last-child {
  margin-right: 0;
}

.main-nav a {
  color: #ffffff;
  text-decoration: none;
}

.main-nav a:hover {
  text-decoration: underline;
}

.main-nav a:active {
  color: rgba(255, 255, 255, 0.3);
}

.btn {
  display: inline-block;
  width: 146px;
  padding: 10px;
  font: inherit;
  vertical-align: top;
  text-align: center;
  color: #a38b70;
  text-transform: uppercase;
  text-decoration: none;
  word-wrap: break-word;
  border: 2px solid #a38b70;
  border-radius: 2px;
}

.btn:hover {
  color: #8d745a;
  border-color: #8d745a;
}

.btn:active {
  color: rgba(141, 116, 90, 0.3);
  border-color: #8d745a;
}

.btn-quick-order {
  float: right;
  margin-top: 6px;
  color: #ffffff;
  border-color: #ffffff;
}

.btn-quick-order:hover {
  color: #404040;
  background-color: #ffffff;
  border-color: #ffffff;
}

.btn-quick-order:active {
  color: rgba(64, 64, 64, 0.3);
  background-color: #ffffff;
  border-color: #ffffff;
}

.promo {
  font-weight: bold;
  font-size: 45px;
  line-height: 55px;
  font-family: "Georgia", serif;
  text-align: center;
}

.promo a {
  color: #ffffff;
  text-decoration: none;
}

.features {
  padding-top: 50px;
  padding-bottom: 55px;
}

.features ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

.feature-item {
  position: relative;
  float: left;
  width: 279px;
  padding-top: 90px;
  padding-right: 30px;
  padding-left: 30px;
  text-align: center;
  border-left: 1px solid #d9d9d9;
}

.feature-item:first-child {
  border-left-color: transparent;
}

.feature-item::before {
  content: "";
  position: absolute;
  top: 0;
  left: 137px;
  width: 65px;
  height: 65px;
  background-image: url("img/sprite.png");
  background-repeat: no-repeat;
}

.feature-choice::before {
  background-position: -5px -5px;
}

.feature-quality::before {
  background-position: -5px -76px;
}

.feature-safety::before {
  background-position: 1px -143px;
}

.feature-title {
  margin: 0;
  margin-bottom: 20px;
  font-weight: bold;
  font-size: 30px;
  line-height: 30px;
  font-family: "Georgia", serif;
  color: #a38b70;
}

.feature-item p {
  margin: 0;
}

.cat-reference {
  padding-top: 70px;
  padding-bottom: 90px;
  background-color: #f2f2f2;
}

.cat-reference .container {
  position: relative;
}

.section-title {
  margin: 0;
  margin-right: 180px;
  margin-bottom: 60px;
  font-weight: bold;
  font-size: 45px;
  line-height: 55px;
  font-family: "Georgia", serif;
  color: #a38b70;
}

.to-full-reference {
  position: absolute;
  top: 5px;
  right: 0;
}

.cat-reference dl {
  width: 830px;
  margin: 0;
  padding: 0;
}

.cat-reference dt {
  margin: 0;
  margin-bottom: 10px;
}

.cat-reference dd {
  position: relative;
  min-height: 100px;
  margin: 0;
  padding-left: 130px;
}

.cat-reference dd img {
  position: absolute;
  top: 0;
  left: 0;
  width: 300px;
  height: 300px;
  border-radius: 5px;
}

.cat-reference dd p {
  margin: 0;
  margin-left:200px;
}

.theory-container:first-child {
  margin-bottom: 70px;
}

.reference-title {
  font-weight: bold;
  font-size: 24px;
}

.reference-source {
  font-weight: normal;
  font-size: 16px;
  color: #666666;
  font-style: italic;
}

.reference-source a {
  position: relative;
  color: #a38b70;
}

.reference-source a:hover {
  color: #8d745a;
}

.reference-source a:active {
  color: rgba(141, 116, 90, 0.3);
}

.reference-source a::after {
  content: "";
  position: absolute;
  top: 0;
  right: -10px;
  width: 8px;
  height: 8px;
  background: url("img/sprite.png") no-repeat -5px -210px;
}

.reviews {
  padding-top: 70px;
  padding-bottom: 90px;
}

.reviews .container {
  position: relative;
}

.to-all-reviews {
  position: absolute;
  top: 0;
  right: 0;
}

.review-item {
  float: left;
  width: 377px;
  margin: 0;
  margin-right: 80px;
  padding: 0;
  padding-left: 50px;
  border-left: 3px solid #a38b70;
}

.review-item p {
  margin: 0;
  margin-bottom: 15px;
}

.review-author {
  font-weight: bold;
  font-style: italic;
}

.popular-and-price {
  padding-top: 70px;
  padding-bottom: 90px;
  background-color: #f2f2f2;
}

.popular-and-price .container {
  position: relative;
}

.popular-items {
  margin-bottom: 50px;
}

.to-catalog {
  position: absolute;
  top: 0;
  right: 0;
}

.catalog-item {
  position: relative;
  float: left;
  width: 262px;
  margin-right: 48px;
  padding: 15px 22px;
  padding-top: 221px;

  border: 1px solid #d8d8d8;
}

.catalog-item:last-child {
  margin-right: 0;
}

.catalog-item img {
  position: absolute;
  top: 0;
  left: 0;
  width: 306px;
  height: 206px;
}

.catalog-item h3 {
  float: left;
  max-width: 150px;
  margin: 0;
  margin-bottom: 10px;
  font-size: 16px;
  color: #000000;
}

.catalog-item-price {
  float: right;
  max-width: 70px;
  margin-bottom: 10px;
  margin-right: 20px;
}

.catalog-item .btn {
  width: 101px;
  color: #ffffff;
  background-color: #a38b70;
}

.catalog-item .btn:hover {
  background-color: #8d745a;
}

.catalog-item .btn:active {
  color: rgba(255, 255, 255, 0.3);
}

.catalog-item .btn-info {
  float: left;
  clear: left;
}

.catalog-item .btn-buy {
  float: right;
}



.feedback {
  padding-top: 60px;
  padding-bottom: 70px;
}

.feedback .container {
  position: relative;
}

.feedback .section-title {
  max-width: 500px;
}

.feedback-tip {
  position: absolute;
  top: 0;
  right: 0;
  max-width: 500px;
}

.feedback-form {
  width: 630px;
  padding-right: 390px;
  background-image: url("img/write.jpg");
  background-repeat: no-repeat;
  background-position: 100% 40px;
}

.feedback-form-group {
  margin-bottom: 15px;
}

.feedback-form-group-left-part {
  float: left;
}

.feedback-form-group-right-part {
  float: right;
}

.feedback-form-group-left-part,
.feedback-form-group-right-part {
  width: 290px;
}

.feedback-form-group label {
  display: inline-block;
  padding: 5px 0;
  padding-left: 17px;
  font-size: 12px;
  text-transform: uppercase;
}

.feedback-form input[type="text"],
.feedback-form select,
.feedback-form textarea {
  box-sizing: border-box;
  width: 100%;
  height: 54px;
  padding: 9px 15px;
  font: inherit;
  color: inherit;
  border: 2px solid #d5d5d5;
}

.feedback-form input[type="text"]:hover,
.feedback-form select:hover,
.feedback-form textarea:hover {
  border-color: #bebebe;
}

.feedback-form input[type="text"]:focus,
.feedback-form select:focus,
.feedback-form textarea:focus {
  border-color: #8d745a;
}

.feedback-form textarea {
  display: block;
  min-height: 120px;
}

.checkbox-area {
  margin-bottom: 25px;
  padding-top: 25px;
  padding-bottom: 25px;
  padding-left: 17px;
  border-bottom: 1px solid #d5d5d5;
}

.checkbox-area input[type="checkbox"] {
  margin: 0;
  margin-right: 5px;
}

.feedback-form .btn {
  margin-top: 40px;
  color: #ffffff;
  background-color: #a38b70;
}

.feedback-form .btn:hover {
  background-color: #8d745a;
}

.feedback-form .btn:active {
  color: rgba(255, 255, 255, 0.3);
}

.page-footer {
  padding-top: 45px;
  padding-bottom: 50px;
}

.footer-top {
  margin-bottom: 45px;
}

.footer-logo {
  float: left;
  width: 150px;
  height: 150px;
}

.footer-logo img {
  width: 150px;
  height: 150px;
}

.footer-middle {
  margin-bottom: 50px;
  padding-top: 50px;
}

.footer-middle,
.footer-bottom {
  border-top: 1px solid #5e5e5e;
}

.footer-menu {
  float: left;
  width: 150px;
  margin-right: 20px;
}

.footer-menu h3 {
  margin: 0;
  margin-bottom: 20px;
  font-weight: bold;
  font-size: 24px;
  font-family: "Georgia", serif;
  color: #a38b70;
}

.footer-menu ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

.footer-menu li {
  margin-bottom: 15px;
}

.footer-menu a {
  color: #c3c3c3;
  text-decoration: none;
}

.footer-menu a:hover {
  color: #ffffff;
}

.footer-menu a:active {
  color: rgba(255, 255, 255, 0.3);
}

.footer-bottom {
  padding-top: 50px;
}

.footer-social {
  float: left;
  width: 490px;
  font-size: 0;
}

.footer-social b {
  margin-right: 40px;
  font-weight: bold;
  font-size: 24px;
  font-family: "Georgia", serif;
  color: #a38b70;
}

.social-btn {
  display: inline-block;
  width: 60px;
  height: 60px;
  margin-right: 10px;
  vertical-align: middle;
  color: #ffffff;
  background-image: url("");
  background-repeat: no-repeat;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

.social-btn:hover {
  border-color: rgba(255, 255, 255, 0.3);
}

.social-btn:active {
  border-color: #ffffff;
  opacity: 0.1;
}

.social-btn-vk {
  background-position: 16px -238px;
}

.social-btn-fb {
  background-position: 19px -297px;
}

.social-btn-in {
  background-position: 13px -358px;
}

.footer-copyright {
  float: right;
  width: 236px;
  margin-top: 17px;
  text-align: right;
  color: #ffffff;
  text-transform: uppercase;
}

.footer-copyright .heart {
  display: inline-block;
  width: 27px;
  height: 24px;
  font-size: 0;
  vertical-align: middle;
  background-image: url("");
  background-repeat: no-repeat;
  background-position: -5px -419px;
}

.footer-copyright a {
  color: #ffffff;
  text-decoration: none;
}

.footer-copyright a:hover {
  text-decoration: underline;
}

.footer-copyright a:active {
  color: rgba(255, 255, 255, 0.3);
}</style>
  </head>
  <body>
    <div class="page-header">
      <div class="container">
        <div class="header-top clearfix">
          <div class="header-logo">
            <img src="72_oooo.plus.png" alt="Fischer Fritz" width="150" height="150">
          </div>
          <ul class="main-nav clearfix">
            <li><a href="#">über uns</a></li>
            <li><a href="#">Katalog</a></li>
            <li><a href="#">Bewertungen</a></li>
          </ul>
          <a class="btn btn-quick-order" href="#">bestellen</a>
        </div>
        <div class="promo">
          <a href="#">Katzen-leckereien<br> Fischer Fritz</a>
        </div>
      </div>
    </div>


    <div class="features">
      <div class="container">
        <ul class="clearfix">
          <li class="feature-item feature-choice">
            <h2 class="feature-title">Auswahl</h2>
            <p>Ihr Haustier wird die Breite unserer Auswahl an leckereien zu schätzen wissen.</p>
          </li>
          <li class="feature-item feature-quality">
            <h2 class="feature-title">Qualität</h2>
            <p>Unsere waren tragen keinen Schaden für Ihre Katzen.</p>
          </li>
          <li class="feature-item feature-safety">
            <h2 class="feature-title">Sicherheit</h2>
            <p>Alles wird aus natürlichen Inhaltsstoffen hergestellt, die für Katzen sicher sind.</p>
          </li>
        </ul>
      </div>
    </div>


    <div class="cat-reference">
      <div class="container">
        <h2 class="section-title">Ein wenig über uns</h2>
        <a class="btn to-full-reference" href="#" title=" über uns öffnen"> über uns</a>
        <dl>
          <div class="theory-container">
            <dt class="reference-title">
              unsere Fabrik
            </dt>
            <dd>
              <img src="tCuyPDzBY4g.jpg" alt="unsere Fabrik" width="300" height="300">
              <p>
              
              
              </p>
            </dd>
          </div>
          <div class="theory-container">
            <dt class="reference-title">
            </dt>
            <dd> 
            </dd>
          </div>
        </dl>
      </div>
    </div>


    <div class="reviews">
      <div class="container">
        <h2 class="section-title">Zufriedene Katzen</h2>
        <a class="btn to-all-reviews" href="#" title="Alle Bewertungen anzeigen">Alle Bewertungen</a>
        <div class="reviews-list clearfix">
          <blockquote class="review-item">
            <p>Vielen Dank für die lange anfallende Idee! Mit Huhn, mit Fisch, mit Wiener Würstchen B-)</p>
            <cite class="review-author">Barsik, st. Berlin</cite>
          </blockquote>
          <blockquote class="review-item">
            <p>Ich kann einfach nicht ohne Süßigkeiten und jetzt nicht brauchen, um die Gastgeberin in den laden zu ziehen, bestelle alles auf Ihrer Website Online!</p>
            <cite class="review-author">Murka, st. Bonn</cite>
          </blockquote>
        </div>
      </div>
    </div>


    <div class="popular-and-price">
      <div class="container">
        <h2 class="section-title">Bestseller</h2>
        <a class="btn to-catalog" href="#" title="Katalog">Katalog</a>
        <div class="popular-items clearfix">
          <div class="catalog-item">
            <img src="nz_mini_chocolate_coated_fish.jpg" alt="Klassiker des Genres»" width="306" height="206">
            <h3>Fische «Classic», mit Fisch</h3>
            <b class="catalog-item-price">3 Eu<br>/100 Gr</b>
            <a class="btn btn-info" href="#">Beschreibung</a>
            <a class="btn btn-buy" href="#">kaufen</a>
          </div>
          <div class="catalog-item">
            <img src="kreker-rybki-ya.jpg" alt="Fisch mit saftigem Fleisch" width="306" height="206">
            <h3>Fisch mit saftigem Fleisch</h3>
            <b class="catalog-item-price">4 Eu<br>/100 Gr</b>
            <a class="btn btn-info" href="#">Beschreibung</a>
            <a class="btn btn-buy" href="#">kaufen</a>
          </div>
          <div class="catalog-item">
            <img src="Шоколадные-рыбка-и-дельфин.jpg" alt="Fisch mit Wiener Brustwarzen" width="306" height="206">
            <h3>Fisch mit Wiener Brustwarzen</h3>
            <b class="catalog-item-price">5 Eu<br>/100 Gr</b>
            <a class="btn btn-info" href="#">Beschreibung</a>
            <a class="btn btn-buy" href="#">kaufen</a>
          </div>
        </div>

        
      </div>
    </div>


    <div class="feedback">
      <div class="container">
        <h2 class="section-title">Noch Fragen?</h2>
        <p class="feedback-tip">Kontaktieren Sie uns und wir werden Ihre verbleibenden Zweifel zerstreuen!</p>
        <form class="feedback-form" action="/keksby-mail" method="post">
          <div class="feedback-form-group">
            <label for="fullname">Stellen Sie sich bitte vor:</label>
            <input type="text" name="fullname" id="fullname">
          </div>
          <div class="clearfix">
            <div class="feedback-form-group feedback-form-group-left-part">
              <label for="phone">Telefonnummer:</label>
              <input type="text" name="phone" id="phone">
            </div>
            <div class="feedback-form-group feedback-form-group-right-part">
              <label for="email">E-Mail:</label>
              <input type="text" name="email" id="email">
            </div>
          </div>
          <div class="checkbox-area">
            <label>
              <input type="checkbox" name="subscription">
              Ich Stimme zu, Spam und SMS am Telefon zu erhalten
            </label>
          </div>
          <div class="feedback-form-group">
            <label for="topic">Thema der Behandlung:</label>
            <select name="topic" id="topic">
              <option value="1">Lieferbedingungen</option>
              <option value="2">Retoursendung</option>
              <option value="3">Beschwerde bei Rospotrebnadzor</option>
            </select>
          </div>
          <div class="feedback-form-group">
            <label for="message">Text der Anfrage:</label>
            <textarea name="message" id="message"></textarea>
          </div>
          <input class="btn" type="submit" value="Senden">
        </form>
      </div>
    </div>


    <div class="page-footer">
      <div class="container">
        <div class="footer-top clearfix">
          <div class="footer-logo">
            <img src="72_oooo.plus.png" alt="" width="100" height="100">
          </div>
          <a class="btn btn-quick-order" href="#">Bestellen</a>
        </div>

        

        <div class="footer-bottom clearfix">
          <div class="footer-social">
            
            
          </div>
        </div>
      </div>
    </div>

  </body>
</html>
