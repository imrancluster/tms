# TMS

Simple Task Management App using Drupal 7. This project was learning purpose for beginners.

Database stored in backup-db folder.

Admin user info
===============
User: admin

Pass: admin

Settings
=======
To change the database info, open the settings.php file from sites/default/settings.php

Then find the following code

```$databases = array (
  'default' => 
  array (
    'default' => 
    array (
      'database' => 'tms',
      'username' => 'root',
      'password' => '',
      'host' => 'localhost',
      'port' => '',
      'driver' => 'mysql',
      'prefix' => '',
    ),
  ),
);```
