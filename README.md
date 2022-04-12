# Multics-auto-exchange-php7.2-all-multics-version-supported
Auto Multics Exchanger files for php7.2 [All Multics version supported]

A-Z all multics version supported.

All php version supported.

Multiple cache share supported

Ajax supported.

fake user, pass protection added.

# Fresh installation for ubuntu 18.04.

apt-get update && apt-get upgrade -y && apt-get install unzip nano apache2 wget -y

sudo apt-get install php7.2-fpm php7.2-common php7.2-dev php7.2-curl php7.2-gd php7.2-json php7.2-mysql php7.2-odbc php7.2-pgsql php7.2-pspell php7.2-readline php7.2-sqlite3 php7.2-tidy php7.2-xml php7.2-xmlrpc php7.2-bcmath php7.2-bz2 php7.2-intl php7.2-mbstring php7.2-phpdbg php7.2-soap php7.2-zip php-imagick php-gettext php-redis php-memcached -y

sudo apt-get install libapache2-mod-php7.2 -y

# now upload all zip files in server

/var/www/html/  or  if you using main index page then => /var/www/html/ex/ folder

Now edit config.php and set there your multics login or cache, cccam, mgcamd port or editors ID's where cache.cfg , cccam.cfg , mgcamd.cfg files included.
