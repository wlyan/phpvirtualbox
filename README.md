# About

phpVirtualBox is from 2017 maintained by Smart Guide Pty Ltd (tudor at smartguide dot com dot au)

with support from various contributors (see https://github.com/phpvirtualbox/phpvirtualbox/graphs/contributors)

Originally Copyright (C) 2015 Ian Moore (imoore76 at yahoo dot com)

FREE, WITHOUT WARRANTY:

All files of this program (phpVirtualBox) are distributed under the
terms contained in the LICENSE.txt file in this folder unless otherwise
specified in an individual source file. By using this software, you are
agreeing to the terms contained therein. If you have not received and read
the license file, or do not agree with its conditions, please cease using
this software immediately and remove any copies you may have in your
possession.

# Installation from Zip file

1) Download zip file from sourceforge project site: https://sourceforge.net/projects/phpvirtualbox/

2) Unzip zipfile into /usr/share/phpvirtualbox

3) Rename config.php-example to config.php and edit as needed.

4) Move phpvirtualbox.conf into /etc/apache2/conf-available/

5) Run `a2enconf phpvirtualbox` and `service apache2 reload`

# Post installation

Default login is username: admin password: admin

Please report bugs / feature requests to GitHub
https://github.com/phpvirtualbox/phpvirtualbox/issues

# Password Recovery

Rename the file recovery.php-disabled to recovery.php, navigate to it in
your web browser, and follow the instructions presented.
