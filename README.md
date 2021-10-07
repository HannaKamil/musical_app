# musical_app
  Musical app contian:
* **artists can register as normal users and then login** (/login) to his own dashborad to can make the following:
- Add his events properities
- Add his location
- Add his venues

*  **Admin panel part contian:**
- All artists users, events, location...etc

* **In front user page can make:**
* can search on all events registered using 
- event type
- People amount
- Select location from all locations registered via artists
- Show all venus registerd




Front-end part is taken from Homespace theme by Colorlib and transformed into Laravel Blade and assets.
Admin part is fully generated with QuickAdminPanel.


 **How to use**   

1- Clone the repository with git clone  
2- Copy .env.example file to .env and edit database credentials there  <br>
3- Run composer install   
4- Run php artisan key:generate   
5- Run php artisan migrate --seed (it has some seeded data for your testing)   
That's it: launch the main URL.
You can login to **adminpanel** by going go **/login** URL and login with credentials: **Email** => admin@admin.com && **Password** => password
