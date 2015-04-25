# Discontinued #

While I had good intentions for this project I eventually forgot about it. It was primarily used for a specific situation where a clients web server was damaged and we needed to get as much data off it before we tried to repair it.

You can find a very good fork of this project at the link below. It's significantly improved over my version.

https://github.com/clouddueling/mysqldump-php

# Database MySQLDump #
_A MySQL to PHP Dump Class and Control script.._


Database MySQLDump is a script written in PHP for dumping entire database's into a MySQL import friendly format. This script is based off my own ideas as well as looking at others scripts that do similar tasks. The generalized aim of this project is to create an all in one light-weight script that does all of the tasks other scripts do plus more. To read more about the aim, read below.

## Project Aim: ##
This project is aimed at developing a simple, XHTML 1.0 Strict Markup valid PHP MySQLDump Class and control page. Eventual goals are to support dumping data into a .sql and .sql.gz file, having a control script that requires user input to select the Server, Database Name, User Name, Password, and if to include DROP statements in the drop.

It's aimed that the script remains XHTML 1.0 Strict friendly according to W3C (World Wide Web Consortium) Markup standards. It's also aimed that the script itself remains completely light weight as to prevent problems with the dump itself, as many databases can be quite large.

Other possible additions once time goes on is on server backups to .sql or .sql.gz files, as well as the addition to creating customized cronjob backup scripts for your website automatically (user would have to direct their web server to the cronjob script).

Additional goal is to maintain a relatively easy to use control file that anyone can edit. Keeping the inner workings of the script stored in the class file is the main method of ensuring this. Anyone can make their own control file, as long as they print the Copyright line for the Class Script (included in the sample Control file).