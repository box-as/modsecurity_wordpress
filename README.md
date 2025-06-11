# ModSecurity Rules for WordPress Protection

Download using:
```
git@github.com:box-as/modsecurity_wordpress.git
```
<br>


✅ What's Included:<br>
Rate limiting for wp-login.php and xmlrpc.php (not blocked outright)<br>
Bad bots detection by User-Agent<br>
Sensitive file access prevention<br>
HTTP method restriction<br>
<br>




📌 To Use in WHM:<br>
Upload the file to your server, e.g., /etc/apache2/conf.d/modsec_vendor_configs/modsec_wordpress_rules.conf.<br>
Open WHM → ModSecurity™ Tools → Rules List.<br>
Click "Edit Rules", and add following line.
```
Include "/etc/apache2/conf.d/modsec_vendor_configs/modsec_wordpress_rules.conf"
```

Tick on "Deploy and Restart Apache" and Save it.
