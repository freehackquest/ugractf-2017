- находим упоминание про поискового паука
- поиск в интернете говорит нам о том что поисковые системы используют карту сайта, для индексации
- согласно стандарту, файл называется sitemap.xml
- скачиваем файл и ищем некие отклонения от стандарта
- в середине документа находим комментарий <!-- try 441561 -->
- переходим по сслыке "https://spider-map.herokuapp.com/441561"
- видим отличие "Very close"
- открываем исходный код страницы и видим флаг в комментарии
