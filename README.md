# rankwatch17_php_userlogin


The task was to build a login system and a registration page too and do proper validation.

The login is build with proper valiation . The registration is build with all validation in php and Js and the inputs are processed with prepared statements. The email is being check for duplicasy with ajax and for country I have used typeahead js with Json query and according to the country state list is being fetched using ajax.

Filewise info:
Index.php:.........    either it will redirect the user in to login page or signup for new user.This file also include form validation through java script. it include database configuration file which is dbConfig.php' and './conn.php'
 dbConfig.php:......... this file is use to  Connect and select the database contain the info related to dtabase like $dbHost = 'localhost';$dbUsername = 'root';$dbPassword = '';$dbName = 'gaurav';
 
home.php.................If session is not set then redirect to Login Page if session is set then show all the details regarding to perticuler user which we ginvn during login time
ajexData.php................It Include database configuration file. it display Country List which is saved in to database and also display state list accordingly to country which you have selected before.

so this is all about loging page . The sessions are used properly and works well.
