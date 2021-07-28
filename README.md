<div style="display:block;">
<br><a href="https://www.youtube.com/watch?v=zgslPfPuUOQ">ВИДЕО ОБЗОР ПРИЛОЖЕНИЯ</a><br>
<a href="https://drive.google.com/file/d/1-4_BciUUcnuochYOk77TYoLuq_BFciqA/view?usp=sharing">Скачать Бета-версию приложения</a>
</div>
  <center><h2>🎬 Онлайн кинотеатр с открытым исходным кодом</h2></center>
<p>Мой первый полноценный pet project 🙂 Он работает на 3х API (video cdn, kinopoisk api и unofficial kinopoisk api)</p>
<p>Проект не расчитан на монетизацию, планируется развивать и совершенствовать.</p>
<h2>⚙ Технологии</h2>
<ul>
  <li>Всё приложение построено на  MVVM архитектуре</li>
  <li>Используются архитектурные компоненты (Room, ViewMode, LiveData)</li>
  <li>Для работы с базой данных используется Room</li>
  <li>Для работы с API используется Retrofit</li>
  <li>Для кэширование и загрузки изображений используется Picasso</li>
  <li>Управление потоками через Coroutines</li>
  <li>Реализация иньекции зависимостей чере Dagger 2</li>
  <li>Периодическая проверка данных с сервера через WorkManager</li>
  <li>Парсинг XML через собственную библиотеку <a href="https://github.com/mrtwon/SimpleXmlParser">SimpleXmlParser</a></li>
</ul>
<h2>✅ Особенности</h2>
<ul>
  <li>🚫 Нет навязчевой и всплывающей google рекламы</li>
  <li>🚫 Отсутствует любая реклама в видео плеере</li>
  <li>🔍  Поиск по описанию, можно с лёгкостью найти фильм который забыли либо найти подходящий</li>
  <li>📚 Тянет за собой базу данных, за счёт чего есть офлайн поиск, быстрый поиск и выборка по жанрам</li>
  <li>📚 Обновление конкретного фильма который недавно вышел</li>
  <li>📺  Не используется видео плеер, вместо этого используется WebView с js плеером</li>
  <li>✅Подписка на новые эпизоды любимого сериала</li>
</ul>
<h2>⚠ Минусы приложения</h2>
<ul>
  <li>Из за того что тянет базу данных - увеличивается вес приложения, база данных весит около 100 мб</li>
</ul>
<h1>Перед сборкой обьязательно <a href="https://drive.google.com/file/d/1-PsdvlzsJtLJxNERfDvGwTp7W70jUqT5/view?usp=sharing">скачайте</a> и перенесите файл database в папку assets (не удалось включить его в проект из-за ограничений github)</h1>
<p>
<img style="width:300px;height:650px;"src="https://i.ibb.co/3y819Zh/screen-home.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/tBYbq7m/screen-category.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/8gvpGbT/screen-show-category.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/Xzdf7hy/screen-favorite.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/KVm677G/screen-about-content.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/t4D7hmM/screen-update.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/yfMHZLv/screen-update-search.jpg"/>
<img style="width:300px;height:650px;"src="https://i.ibb.co/J324b1R/screen-search-description.jpg"/>
</p>
