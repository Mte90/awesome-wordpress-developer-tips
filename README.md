#Awesome WordPress Developer Tips
> Curated list that contain very awesome and ready code, snippets or examples without libraries or external packages made it for developers.

##Why
This list is born from a real workflow in my development in WordPress, sometimes you don't need or not exist a library that do a specific stuff very well with a real case to study.  
When i need something like that i search for other plugins that do that stuff to study and replicate, better if possible. For that reason i remember many plugins what they do and i search for recreate the same UX/UI. This list infact contain reference to plugins or docs but not to tutorials.  
In this way is possible see in action also the workaround used and more important a case study.  
In few words this is a list for skilled WordPress developers that want a simple way to found specific code (in the mainly case that use an hook).  

PS: Part * is used because sometimes the code is splitted (maybe an hook declaration and a function).  
PSS: Sometimes the code can be in the wrong line because the line is changed, search in that page or open a ticket to fix that page.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Table of Contents

- [Core](#core)
- [AJAX](#ajax)
- [JSON REST API official](#json-rest-api-official)
- [External plugin](#external-plugin)
- [Other lists](#other-lists)

##Core

* Add backend/frontend fields in comments - Code from [DaTask](https://wordpress.org/plugins/datask/) plugin: [Part 1](https://github.com/Mte90/DaTask/blob/master/public%2Fincludes%2FDT_Comment.php)
* Add Screen Option in contextual tabs - Code from [DaTask](https://wordpress.org/plugins/datask/) plugin: [Part 1](https://github.com/Mte90/DaTask/blob/master/admin%2Fclass-datask-admin.php#L186), [Part 2](https://github.com/Mte90/DaTask/blob/master/admin%2Fclass-datask-admin.php#L54)
* Add links to Plugin in Plugin list - Code from [DaTask](https://wordpress.org/plugins/datask/) plugin: [Part 1](https://github.com/Mte90/DaTask/blob/master/admin%2Fclass-datask-admin.php#L214), [Part 2](https://github.com/Mte90/DaTask/blob/master/admin%2Fclass-datask-admin.php#L60)
* Add links to User in User list with action - Code from [DaTask](https://wordpress.org/plugins/datask/) plugin: [Part 1](https://github.com/Mte90/DaTask/blob/master/admin%2Fincludes%2FDT_User_Backend.php)
* Add link in menu top bar - Code from [WP Find Function](https://wordpress.org/plugins/find-function) plugin: [Part 1](https://github.com/Mte90/WP-Find-Function/blob/master/find-function.php#L46), [Part 2](https://github.com/Mte90/WP-Find-Function/blob/master/find-function.php#L92)
* Add custom post type in search box - Code from [WordPress Plugin Boilerplate Powered](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered): [Part 1](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fpublic%2Fclass-plugin-name.php#L130), [Part 2](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fpublic%2Fclass-plugin-name.php#L311)
* Add custom post type in Activity Dashboard widget - Code from [WordPress Plugin Boilerplate Powered](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered): [Part 1](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fadmin%2Fclass-plugin-name-admin.php#L85), [Part 2](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fadmin%2Fclass-plugin-name-admin.php#L402)
* Add custom post type in At Glance Dashboard widget - Code from [WordPress Plugin Boilerplate Powered](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered): [Part 1](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fadmin%2Fclass-plugin-name-admin.php#L83), [Part 2](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fadmin%2Fclass-plugin-name-admin.php#L374)
* Detect the page in backend - Code from [AdRotate Extra Settings](https://wordpress.org/plugins/adrotate-extra-settings/) plugin: [Part 1](https://github.com/Mte90/AdRotate-Extra-Settings/blob/master/admin%2Fclass-adrotate-extra-settings-admin.php#L57)
* Load a text domain - Code from [WordPress Plugin Boilerplate Powered](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered): [Part 1](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/blob/master/plugin-name%2Fincludes%2Fload_textdomain.php)
* Nonce for guest user - [Snippet](https://gist.github.com/Mte90/a1b6443aabe14386fa3b)

##AJAX

* AJAX request for non-logged user [`wp ajax nopriv_(action)`](https://codex.wordpress.org/Plugin_API/Action_Reference/wp_ajax_nopriv_%28action%29)
* AJAX request for logged user [`wp ajax_(action)`](https://codex.wordpress.org/Plugin_API/Action_Reference/wp_ajax_%28action%29)
* Use [`wp_send_json()`](https://codex.wordpress.org/Function_Reference/wp_send_json),[`wp_send_json_success()`](https://codex.wordpress.org/Function_Reference/wp_send_json_success) and [`wp_send_json_error()`](https://codex.wordpress.org/Function_Reference/wp_send_json_error) for standard JSON request in AJAX request.

##JSON REST API official

* Add meta field on v1 and v2 in readonly - Code from [DaTask](https://wordpress.org/plugins/datask/) plugin: [Part 1](https://github.com/Mte90/DaTask/blob/master/public%2Fincludes%2FDT_API.php)

##External plugin

* Support for BadgeOS trigger - Code from [DaTask](https://wordpress.org/plugins/datask/) plugin: [Part 1](https://github.com/Mte90/DaTask/blob/master/public%2Fincludes%2FDT_BadgeOS.php)

##Other lists

* WordPress Plugin Boilerplate Powered - [External useful resources](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered/wiki/Useful-resources-or-code-examples)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Daniele Scasciafratte](http://mte90.net) has waived all copyright and related or neighboring rights to this work.