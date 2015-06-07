to update the website, sign in to server and run following code:
```
cd /var/www/hackclubslhs.com.git/HackClub-SLHS.github.io
sudo git fetch --all
sudo git reset --hard origin/master
sudo git pull origin master
sudo service apache2 reload
```
