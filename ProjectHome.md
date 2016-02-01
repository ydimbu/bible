# INSTALLATION INSTRUCTIONS #

**1  Download version 4.0 of software via:
https://code.google.com/p/bible/downloads/list**

**2 Extract the .zip file using a self-extractor such as WinZip.com. Once extracted you will have the following files and folders present:**

/mysql/
/upload/
install-help.txt

**3 Log onto your server and create a mysql database, and user.**

**4 Login in to the database with PhpmyAdmin and import the /mysql/bibledb\_kjv.sql file into this new database that you created.
(This file will self populate all sql tables needed.)**

**5 Edit the data\config.inc.php with a text editor such as notepad and enter your database details, such as username, password and localhost. Just a heads up, localhost in most cases is usually called "localhost".**

// The Database Host Name
$dbHost="localhost";

// The Database Name
$dbName="XXXXX\_XXXXX";

// The Database User Name
$dbUser="XXXXX\_XXXXX";

// The Database Password
$dbPassword="XXXXXXXXXXX";

**6 Upload all files that are inside the /upload/ folder to your domain in binary mode. ( I use Filezilla, WS FTP, or Cute FTP). In most cases you will probably want to upload the files to the root of your domain such as /home/www/example.com/.**

# THANK YOU #

For the latest updates please visit: http://bookinthebible.com/bible-books-software/

Have a blog? Then get our Bible Reference WordPress Plugin at: http://bookinthebible.com/wordpress-plugin/bible-automatic-links.zip

Thanks for trying our software. More importantly, thanks for sharing the Word of God on your website!