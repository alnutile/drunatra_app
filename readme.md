# Setup

there is an .env_boot.php file in the root folder. This sets you environment by returning
'local' or 'prod' etc.

then there is a .env file to set the variables for your machine/server.

This would be

~~~
DB_HOST=localhost
DB_USER=foo
DB_PASS=bar
~~~

etc. This helps to easily setup variables per setup but keeps it out of git.
