<!DOCTYPE html>
<html lang="ru-RU">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Детский сад с Султанмуратово</title>
  <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Open+Sans:400,400italic,600,600italic,700,700italic|Playfair+Display:400,700&subset=latin,cyrillic">
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.4.0/css/font-awesome.css">
  <link rel="stylesheet" type="text/css" href="style.css">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>  
</head>
<body>
<header>
    <nav class="container">
      <a class="logo" href="">
        Филиал муниципального бюджетного общеобразовательного учреждения Средняя общеобразовательная школа д.Курманаево муниципального района Аургазинский район Республики Башкортостан «Детский сад с.Султанмуратово"
      </a>
      <div class="nav-toggle"><span></span></div>
      <ul id="menu">
        <li><a href=".\index.html">Детский сад</a></li>
        <li><a href=".\time.html">Распорядок дня</a></li>
        <li><a href=".\teacher.html">Педагоги</a></li>
		<li><a href=".\address.html">Адрес</a></li>
        <li><a href=".\doc.html">Нормативные документы</a></li>        
      </ul>
    </nav>
  </header>
  <div class="container">
  <div class="posts-list">
    <article id="post-1" class="post">
      <div class="post-image"><a href=""><img src=".\DS.jpeg"></a></div>
      <div class="post-content">
        <h2 class="post-title">Детский сад</h2>
        <p>Детский садик с. Султанмуратово расположен в живописном месте</p>
        </div>      
    </article>
    <article id="post-2" class="post">
      <div class="post-image"><a href=""><img src=".\TER.jpeg"></a></div>
      <div class="post-content">
        <h2 class="post-title">Детская площадка</h2>
        <p>На территории расположена игровая площадка и веранда</p>        
        </div>	   
          </article>	
  </div> <!-- конец div class="posts-list"-->
  <aside>
  <div class="widget">
    <h3 class="widget-title">Категории</h3>
    <ul class="widget-category-list">
      <li><a href=".\news.html">Новости</a></li>
      <li><a href=".\events.html">Мероприятия</a></li>
      <li><a href=".\study.html">Обучение</a></li>
    </ul>
  </div>  
</aside>
</div> <!-- конец div class="container"-->
<footer>
  <div class="container">
    <div class="footer-col"><span>Детский сад с.Султанмуратово</span></div>
    <div class="footer-col">
      <span>2022</span>
    </div>
    
  </div>
</footer>
</body>
	<script>
$('.nav-toggle').on('click', function(){
  $('#menu').toggleClass('active');
});
</script>
</html>
