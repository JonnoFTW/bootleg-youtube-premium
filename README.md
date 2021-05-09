# ios-youtube-dl
I don't like paying $15 a month to listen to youtube videos with my phone locked 

## Server-Side installation 

```bash 
apt install youtube-dl nginx php

https://github.com/NotJoeMartinez/bootleg-youtube-Premium

rm /var/www/html/*.html
mkdir /var/www/html/movies/

mv bootleg-youtube-Premium/html/index.php /var/www/html/

systemctl start nginx
```

## iOS installation 

You'll need to use the [shortcuts](https://apps.apple.com/us/app/shortcuts/id915249334) app for this. It has a feature that allows you
to run scripts over ssh.      

![im1](imgs/img1.jpg)