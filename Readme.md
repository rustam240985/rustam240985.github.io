# Научиться учиться. Проектная работа №2
Одностраничный сайт посвящен теме обучения, различным методикам и техникам для лучшего усвоения и запоминания новой информации, эффективного распределения личного времени, преодолении прокрастинации, приведены факты и цифры о строении человеческого мозга, полезные ресурсы с материалами о техниках и лайфхаках обучения, книги и видео выступлений специалистов в различных областях.
Для просмотра лендинга можно использовать один из любых браузеров интернета (Chrome, Edge, Safari, Firefox, Opera), желательно последних актуальных версий для корректного отображения всех компонентов страницы сайта.

Сайт использует методологию БЭМ в части именования классов и организации файловой структуры, технологии Flexbox, встроенный контент iframe, CSS-анимацию.

Основная и единственная страница сайта - **_index.html_**

В папке pages размещен файл стилей, подключенный к странице, index.css, в котором при помощи инструкции import подключены файлы стилей для каждого из блоков, используемых на странице, которые в свою очередь расположены в папке blocks. В папке images собраны все изображения, используемые на сайте.

Шапка сайта размечена блоком _header_ и включает в себя логотип сайта, заголовок, подзаголовок, изображение и анимацию.

Контентная часть сайта состоит состоит из 9 независимых блоков:
* _Description._ О главных поблемах в обучении.
* _Techniques._ Техники обучения.
* _Video._ Видео выступлений с конференции TED
* _Oakley._ История Барбары Оакли
* _Feynman._ Метод Фейнмана.
* _Digits._ Цифры и факты
* _Khan._ Книга "Весь мир - школа". Салман Хан
* _Kaufman._ Принципы обучения от Джоша Кауфмана
* _Resources._ Полезные ресурсы

В подвал сайта - блок _footer_, располагается навигация по сайту, ссылки на социнальные сети, логотип и копирайт.

На данный момент страница сайта не адаптирована для корректного отображения на экранах мобильных устройств, в связи с чем необходимо провести дополнительные работы по верстке страницы. Также необходимо для всех ссылок на странице, содержащих в атрибуте href временную "заглушку" в виде символа #, добавить корректный URL для перехода на соответствующие раздел или страницу сайта.
