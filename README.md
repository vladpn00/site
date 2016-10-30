# развертка проэкта
test_site
git clone git@github.com:vladpn00/site.git
cd ./site/
_____
для винды
(C:\bin>echo @php "%~dp0composer.phar" %*>composer.bat)
___

curl -sS https://getcomposer.org/installer | php
/opt/php/5.6/bin/php ./composer.phar update
/opt/php/5.6/bin/php ./init 
##настраиваем подключение к бд
/home/aaz/Source/Web/site_yii2_soc_net/common/config/main-local.php
##запускаем миграцию
yii migrate

Все готово