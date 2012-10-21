ZF2-Module-Template
===================

Zend Framework 2 Module Template helps you to start with creating your own ZF2 modules

USAGE
===================

- Replace all occurance of word "Template" in files and folers names with name of your module, e.g. "Forum"

- Replace all occurance of word "template" in files and folers names with name of your module, e.g. "forum"

- Replace all occurance of "{$module}" in all files with name of your module, e.g. "Forum"

- Replace all occurance of "{$moduleLower}" in all files with name of your module, e.g. "forum"

- Add the module name in the application config file (config/application.config.php), in order to "activate" the module, e.g.:

...
'modules' => array(
	'Application',
	...,
	'Modulename', <-- Add here you module's name
    ),
...

- That's it! Your new module is ready to be used.
