# manifest-dolibarr
Jelastic manifest for Dolibarr

How to install it correctly ?

1.  Go to www.hidora.com  and create an account for free.
2.  In the Marketplace, research “Dolibarr” and install it.
3.  Open your environment in a browser and add  /install at the URL
4.  Click on the “first installation”. 
5.  Add the password that your received in your email for the Database ( MySQL)
6.  And now, create the user and password for the SuperAdmin of your Dolibarr.


How to secure it ? 

1. Via the dashboard, create the file “install.lock” in /var/www/webroot/ROOT/documents/.
2. Change the access right for the file /htdocs/conf/conf.php$ chmod 400  /var/www/webroot/ROOT/htdocs/conf/conf.php
3. You can add a SSL certification to your Dolibarr, change the topology and click on SSL certificate.

Contact the support for more informationor any request : https://support.hidora.com


