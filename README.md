<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>AddOffLine</title>
    <link href="css/bootstrap.css" rel="stylesheet">
    <link href="css/style.css" rel="stylesheet">
    <link rel="stylesheet" href="css/animate.css"> 
    <link rel="stylesheet" href="css/justified-nav.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
  </head>
<body>

<section id="header">

<header>
  <div class="container">
    <div class="row">
      <div class="col-md-6 logo">Ad-OffLine</div>
      <div class="col-md-6 text-right phone">+996705559633</div>
    </div>
  </div>
</header>	

<div class="container">
<div class="row">
  <nav>
    <ul class="nav nav-justified">
      <li class="active"><a href="#">Главная</a></li>
      <li><a href="#">О компании</a></li>
      <li><a href="#">Наши проекты</a></li>
      <li><a href="#">Услуги</a></li>
      <li><a href="#">Контакты</a></li>
    </ul>
  </nav>
</div>
</div>

<section id="slider">
  <div class="container">
     <div class="row">
     <div id="carousel-example-generic" class="carousel slide carousel-fade carousel-animate carousel-bg" data-ride="carousel">

     <ol class="carousel-indicators">
       <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
       <li data-target="#carousel-example-generic" data-slide-to="1"></li>
       <li data-target="#carousel-example-generic" data-slide-to="2"></li>
     </ol>

     <div class="carousel-inner" role="listbox">
       <div class="item active" style="background-image: url(images/slide_1.jpg)">
         <div class="carousel-caption">
           <div class="hero">
             <hgroup class="zoomInDown animated">
               <h2 class="fadeInLeft animated">Заголовок слайдера</h1>
               <h3 class="slideInRight animated">Маленький заголовок слайдера</h3>
             </hgroup>
             <button class="btn btn-hero btn-lg bounceInUp animated" role="button">Кнопка</button>
           </div>
         </div>
       </div>
       <div class="item" style="background-image: url(images/slide_1.jpg)">
         <div class="carousel-caption">
           <div class="hero fadeInUp animated">
           <hgroup>
             <h2>Заголовок слайдера #2</h1>
             <h3>Маленький заголовок слайдера #2</h3>
           </hgroup>
           <button class="btn btn-hero btn-lg zoomIn animated" role="button">Кнопка</button>
           </div>
         </div>
       </div>
       <div class="item" style="background-image: url(images/slide_1.jpg)">
         <div class="carousel-caption">
           <div class="hero rollIn animated">
             <hgroup class="rotateInDownRight animated">
               <h2>Заголовок слайдера #3</h1>
               <h3>Маленький заголовок слайдера #3</h3>
             </hgroup>
             <button class="btn btn-hero btn-lg" role="button">Кнопка</button>
           </div>
         </div>
       </div>
     </div>

     <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
       <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
       <span class="sr-only">Назад</span>
     </a>
     <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
       <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
       <span class="sr-only">Вперёд</span>
     </a>
     </div>

    </div>
  </div>
</section>

</section>

<section id="advantage">
  <div class="container">
    <div class="row">
      <div class="col-md-3 text-center hero fadeInUp animated">
        <img src="images/like.png" alt="">
        <p>Гарантия<br/>качества</p>
      </div>
      <div class="col-md-3 text-center hero fadeInUp animated">
        <img src="images/piggy-bank.png" alt="">
        <p>Низкие<br/>цены</p>
      </div>
      <div class="col-md-3 text-center hero fadeInUp animated">
        <img src="images/star.png" alt="">
        <p>Лучшая<br/>продукция</p>
      </div>
      <div class="col-md-3 text-center hero fadeInUp animated">
        <img src="images/phone-call.png" alt="">
        <p>Всегда<br/>на связи</p>
      </div>
    </div>
  </div>
</section>


<section id="about">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h1><span>Важный</span> текст о компании</h1>
        <p>
          Сайт рыбатекст поможет дизайнеру, верстальщику, вебмастеру сгенерировать несколько абзацев более менее осмысленного текста рыбы на русском языке, а начинающему оратору отточить навык публичных выступлений в домашних условиях. При создании генератора мы использовали небезизвестный универсальный код речей. Текст генерируется абзацами случайным образом от двух до десяти предложений в абзаце, что позволяет сделать текст более привлекательным и живым для визуально-слухового восприятия.
        </p>
        <a href="/" id="btn-more">Подробнее</a>
      </div>
      <div class="col-md-6">
        <img src="images/img.jpg" alt="">
      </div>
    </div>
  </div>
</section>

<section id="message">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <h2><span>Оставить</span> заявку</h2>
         <form id="contact-form" method="post" action="contact.php" role="form">
          <div class="messages"></div>
           <div class="controls">
             <div class="row">
               <div class="col-md-6">
                 <div class="form-group">
                   <label for="form_email">Email *</label>
                    <input id="form_email" type="email" name="email" class="form-control" placeholder="Введите адрес электронной почты*" required="required" data-error="Требуется действующее электронное письмо.">
                   <div class="help-block with-errors"></div>
                 </div>
               </div>
               <div class="col-md-6">
                 <div class="form-group">
                   <label for="form_phone">Телефон</label>
                    <input id="form_phone" type="tel" name="phone" class="form-control" placeholder="Введите свой телефон">
                   <div class="help-block with-errors"></div>
                 </div>
               </div>
             </div>
             <div class="row">
               <div class="col-md-12">
                 <div class="form-group">
                   <label for="form_message">Сообщение *</label>
                    <textarea id="form_message" name="message" class="form-control" placeholder="Напишите нам" rows="4" required="required" data-error="Пожалуйста, оставьте нам сообщение."></textarea>
                   <div class="help-block with-errors"></div>
                 </div>
               </div>
               <div class="col-md-12 text-center">
                  <input type="submit" id="button_contacts" value="Отправить">
               </div>
             </div>
           </div>
         </form>
        </div>
      </div>
    </div>
  </div>
</section>

<footer>
    <div class="container">
      <div class="row">
        <div class="col-md-6 text-left hidden-xs">
          <div id="copyright">
            <p id="copyright-block">© Все права защищены твоей мамой</p>
          </div>
        </div>
        <div class="col-md-6 text-right">
        </div>
      </div>
    </div>
  </footer>

   <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
   <script src="js/bootstrap.js"></script>	
</body>
</html>
