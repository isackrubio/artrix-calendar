## System Requirements ##

Requirements are basics of the PHP web server that can be calendar system set up and running.

Apache -> http://www.apache.org

MySQL -> http://www.mysql.com

PHP (version 4.3.0 or higher) -> http://www.php.net
  * Needs XML support

## Server Configuration ##

You must ensure that PHP has been compiled with support for MySQL in order to successfully run the system. We recommend Apache for running our system on Windows.

## Optional required ##
If you want support for SEF URLs, you'll need mod\_rewrite and the ability to use local .htaccess files.

# Manual Installation #
First of all, download the file package. You can run the calendar system as a subdirectory e.g. http://www.mysite.com/calendar, or you can run it in full site when you finished install, just have to edit the config variable in config.php file

Make a subdirectory for the web site files e.g.
UNIX - /usr/local/www/public\_html/calendar/
Windows - c:\apache\htdocs\calendar

Uncompress this distribution download file into the directory you have created above using Untar or Winzip.

After that you access the website as the files are located e.g. http://localhost/calendar/, you will see the Warning/Error showing in the page then you type the URL to http://localhost/calendar/install for setting values as showing in the figure below.

![http://artrix-calendar.googlecode.com/svn/wiki/screenshot_install.jpg](http://artrix-calendar.googlecode.com/svn/wiki/screenshot_install.jpg)

In this step you just put the database values and it also will check the system availability on the webpage and submit the form. ArTrix calendar will prompt you to delete your Installation folder. This is for security reasons, so that a malicious user cannot change your installation. Until this is done, it will not work.

Your set up has now been completed, and you are ready to run.

You are now looking at main login page and try the initialized users as "admin" with its password is "demo" and go straight to log on.

### Sample Users ###
  * user: admin password: demo
  * user: demo password: demo

Enjoy!