# musical_app

Front-end part is taken from Homespace theme by Colorlib and transformed into Laravel Blade and assets.
Admin part is fully generated with QuickAdminPanel.


*How to use*
Clone the repository with git clone
Copy .env.example file to .env and edit database credentials there
Run composer install
Run php artisan key:generate
Run php artisan migrate --seed (it has some seeded data for your testing)
That's it: launch the main URL.
You can login to adminpanel by going go /login URL and login with credentials: Email => admin@admin.com && Password => password
