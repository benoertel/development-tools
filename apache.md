# Apache

to start it
```sh
sudo apachectl start
```

to stop it
```sh
sudo apachectl stop
```

to restart it
```sh
sudo apachectl restart
```

To find the Apache version
```sh
httpd -v
```

## Configure username.conf

Check that you have a “username.conf” filed under:
/etc/apache2/users/

```sh
<Directory "/Users/benjamin/Sites/">
   Options Indexes MultiViews
   AllowOverride All
   Order allow,deny
   Allow from all
</Directory>
```

## Configure httpd.conf

/etc/apache2/httpd.conf

uncomment
# Virtual hosts
#Include /private/etc/apache2/extra/httpd-vhosts.conf

uncomment
#LoadModule php5_module libexec/apache2/libphp5.so



## vhost

vi /etc/hosts
::1     mkpt.local
