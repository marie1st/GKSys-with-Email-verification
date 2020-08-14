# GKSys-with-Email-verification
Login page of GKSys with Email verification after registration

Step 1  To get the first glimpse
1. git clone this project
2. npm install

Step 2
1. edit .env to your email environment settings.
This project use gmail for example to send out email address, therefore using smtp.gmail.com on 875 port, not 2525.

Step 3  Use this command otherwise the reminder and errors will occur stated that there is no sender address
1. php artisan config:cache

Step 4 run this project
1. npm run dev
2. php artisan serve
