КАК ПУБЛИКОВАТЬ ЭТО В GOOGLE SITES (на телефоне, ~10 минут)

1. sites.google.new (или sites.google.com) -> "Blank" шаблон
2. Название сайта: YouTube Upload Tool
3. Страницы (кнопка "Страницы" -> "Новая страница"):
   - главная: вставить текст из site_home.txt
   - "privacy-policy": вставить site_privacy.txt
   - "terms-of-service": вставить site_terms.txt
4. "Опубликовать" -> веб-адрес: mikimasi-max (получится https://sites.google.com/view/mikimasi-max/...)
   Доступ: "Ограничен: все, у кого есть ссылка" -> это ПУБЛИЧНЫЙ доступ, галочку "ограничить" НЕ включать.
5. Подставить в Google Cloud Console (OAuth consent screen -> Branding):
   App home page:        https://sites.google.com/view/mikimasi-max
   App privacy policy:   https://sites.google.com/view/mikimasi-max/privacy-policy
   Authorized domains:   youtube.com  +  sites.google.com   (пустые строки удалить)
6. В диалоге "Branding verification issues" выбрать "I have fixed the issues" -> Proceed.
   Если Google требует подтвердить владение доменом: Search Console
   (https://search.google.com/search-console) -> Добавить ресурс -> "Префикс URL" ->
   вставить адрес сайта -> Sites: Настройки -> "Подтвердить владеть этим ресурсом" (verify ownership)
   -> добавить TXT-запись, которую покажет Search Console -> подтвердить. Ждать до 24 часов.
