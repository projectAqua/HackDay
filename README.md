# Salmon Hack Day

This is a vanilla Magento build based on the latest codebase as of 13 November 2015

To run this locally you'll need to install the database included under the root with the filename magento1.sql. The database name is magento1.

You may need to make the following changes to your php.ini file if your server is slow:

  - post_max_size = 100M
  - upload_max_filesize = 100M
  - max_execution_time = 600
  - max_input_time = 600
  - memory_limit = 500M

Assuming that you're using *phpMyadmin* to upload the database, if you're still getting timeout errors uploading the database, please change the following setting in \phpmyadmin\libraries\config.default.php

  - $cfg['ExecTimeLimit'] = 0;


> Don't forget to restart the server after making any of the above changes

The username to login to the Magento Backend (http://localhost/admin) is "admin" and the password is "password". Original...

### Version
1.0

Thanks

Faizal
