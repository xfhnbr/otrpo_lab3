## Установка проекта

0.	Убедитесь, что в системе установлены nodejs-v25.1 и выше, php-v8.5 и выше и composer
1.	Скачайте репозиторий
2.	Переименуйте файл ".env.example" в ".env"
3.	Выполните composer install
4.	Выполните npm install
5.	Выполните php artisan key:generate
6.	Выполните php artisan migrate
7.	Выполните php artisan db:seed
8.	Выполните php artisan storage:link
9. 	Для сборки используйте npm run build, npm run dev или npm run watch.
10.	Запустите сервер через php artisan serve