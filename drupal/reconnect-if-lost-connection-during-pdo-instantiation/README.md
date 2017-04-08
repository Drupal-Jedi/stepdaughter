# Patch summary

Fixed problem with lost connection to MySQL in case If wait timeout (MySQL - **wait_timeout**) is out.

_May occur in case of long running Drush commands, or drush daemons. See https://dev.mysql.com/doc/refman/5.7/en/gone-away.html  for details._