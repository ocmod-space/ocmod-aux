#  OC Fixes|PHP8x

## Description
Fix errors and warning appeared on PHP 8.1+:
* `Unknown: preg_replace(): Passing null to parameter #3 ($subject) of type array|string is deprecated in /home/ocmodspace/web/30xx.test.ocmod.space/public_html/a/system/storage/modification/system/engine/action.php on line 66`. Caused by wrong requests such an `index.php?route=any_unknown_route`.
