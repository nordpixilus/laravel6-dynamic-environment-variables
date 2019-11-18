# laravel6-dynamic-environment-variables
Динамическое изменения среды окружения с поддержкой запросов из командной строки.

Dynamic environment changes with command-line query support.
# Установка
Файл по адресу: \bootstrap\app.php.

Код всталяем сразу после инициализации $app.
# Тест
В коммандной строке \vendor\bin\phpunit
 //".env.testing"

Обновление страницы: dd($app->environmentFile());
 //".env.local"
 
 На production будет  //".env"
