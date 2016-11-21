

Testing some things in Drupal 7
===============================


### Modules 
It is good to hand folder modules in this way:
sites/all/modules/contrib
               ../custom


#### Create a module
When you install devel module, folder devel will appear
in the structure of directories.

Usually modules has 2 files .module (code) and .info
(information of the module).

The structure of a hook has to be respected so if the 
name of the module is custom_menu_add and you want a 
hook_menu so the name of the function must be:

function custom_menu_add_menu () {...

so hook=custom_menu_add and it has to ended with *_menu*.


NOTE: Remember about the cache, even you haven't enabled the
cache system, maybe, is possible that you may need to clear
the cache before you would be able to see the changes.
