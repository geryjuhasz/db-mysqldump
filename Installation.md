# Requirements\Specifications #
  * PHP 5
  * MySQL 4.0-5.0 (6.0 possible, but not tested at this stage).


# Installation #

Editable Areas:
  * Class File Location Relative to Control Script {require\_once('./mysqldump.class.php');}
  * $dbhost - The hostname of the MySQL Server. Often localhost.
  * $dbuser - User name for database.
  * $dbpass - Password to match the user name.
  * $dbname - Name of the database you wish to dump.
  * $drop\_table\_if\_exists - Add drop syntax to dump. Will drop tables on import. True\False.

Simply edit the dump.php and upload both files. Open dump.php via a web browser and it will dump the data. We recommend blocking access to the folder the script is located in via .htaccess.

CHMOD Settings:
  * It's recommended to use 755 or 555 CHMOD's so you can access your script anywhere. (555 grants read execute to everyone, 755 additionally grants write rights to OWNER).
  * For added protection 511 will only allow you access to read but no one else, 711 will give you read write rights.

Note: At this time the script does NOT need write rights. So we suggest not using it unless you have a specific purpose in mind.