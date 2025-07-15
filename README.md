# xampp-fix

## Go to bellow files from XAMPP -> Apache - Config
### httpd.conf
  - Go to httpd.conf
  - Find Listen
  - Replace the line with the line below
  - Listen 8090
  - Save the file
### config.inc.php
  - Go to config.inc.php
  - Find host
  - Replace the line with the line below
  - $cfg['Servers'][$i]['host'] = 'localhost:3336';
  - Save the file
## Go to bellow files from XAMPP -> MySQL - Config
  - Go to my.ini
  - Find port=
  - Replace the line with the line below
  - port=3336
  - Save the file
