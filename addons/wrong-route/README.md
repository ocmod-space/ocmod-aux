#  OC Fix|Wrong Route

## Description
Workaround for an PHP 8.1+ error message caused by erroneous requests like `index.php?route=checkout22`.
The error message is `Unknown: preg_replace(): Passing null to parameter #3 ($subject) of type array|string is deprecated in /home/ocmodspace/web/30xx.test.ocmod.space/public_html/a/system/storage/modification/system/engine/action.php on line 66`
