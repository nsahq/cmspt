cmspt
=====

File permission script for Open Source based CMS.
Currently supports the following:
* Drupal
* Wordpress

Next CMS to be added:
* Joomla


To use the script just download it and make sure it's executable (`chmod +x /path/to/script`).
If you want to be able to execute the script by typing its name, place it in `/usr/bin`.

```
Usage example:
cmspt --help

cmspt --dir /home/myuser/public_html --CMS drupal --user myuser

cmspt -d /home/myuser/public_html -c wp -u myuser
```
