WordPress BitNami MAC installation locally:

```
>bitnami.com>Bitnami.com/stacks>WeordPress Installer
```

While install WordPress, it asks to provide username and password. This username and password use to login back-end/admin
Later to access to PhpMyAdmin (database) wee need to use “root” as username and our setup password.
Note:  (During installation uncheck Gmail and uncheck cloud )
note : to see WordPress after install: it should appear on : localhost:8080/wordpress/

How to use Bitnami manager:

To find that (in MAC) : one way is search : command+space and then Manager-OSX .
Other way is:
Manager-OSX is the name of the manager toolbox available from WordPress installation folder.

On back-End/admin delete all plugins instead of Hello Dolly and Aksimet.

Which folder we are targeting:

```
>Application>Wordpress>apps>wordpress>htdocs
```

the hotdogs is the folder of our website with three main folders in.
we can copy and paste the htdocs folder to everywhere and open it with IDEs like Atom.


Then:

```
>wp-content>themes>child(create new folder called child)>style.css(create new file called style.css)

```

inside the style.css:

```

/*  Theme Name: Child of Twenty Sixteen
Template : twenty sixteen

*/

```
