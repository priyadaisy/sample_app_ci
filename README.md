#CodeIgniter + Socket.IO (with Redis) Sample Project

## Part One
## Part One
## Part One
## Part One
The part\_one folder contains a plain old PHP/MySQL project utilizing the CodeIgniter framework. Styling is provided by Twitter Bootstrap.  The application uses the default Session plugin provided by CodeIgniter.
Twitter Bootstrap.  The 
Read More: [A Sample CodeIgniter Application with Login and Session](http://ericterpstra.com/2013/03/a-sample-codeigniter-application-with-login-and-session/ "Part One Blog Link")
 
## Part Two 
## Part Two
Part Two
Part Tworead
These files allow the use of Redis as a storage medium for CodeIgniter's session data instead of a MySQL table.  The MY\_Session class overrides several methods in CodeIgniter's Session class so that persistent session data is stored and retrieved from Redis.

Read More: [Use Redis instead of MySQL for CodeIgniter Session Data](http://ericterpstra.com/2013/03/use-redis-instead-of-mysql-for-codeigniter-session-data/)

## Part Three
Part Three
## Part Three
Part Three
A refactored version of part one.  It includes the changes from part 2, but also features real-time updates using Socket.IO and a NodeJS server.  Data is shared between NodeJS and PHP via Redis.

The user interface is unchanged, but when a message is posted by a user, any other user with the same team ID will instantly recieve the message and have it posted in the team messages list.  Admins will recieve messages from all users, regardless of team ID.  

Read More: [Live Updates in CodeIgniter with Socket.IO and Redis](http://ericterpstra.com/2013/04/live-updates-in-codeigniter-with-socket-io-and-redis/)


Part_one -- The Setu
Part_one -- The Setu
Part_one -- The Setu
Part_one -- The Setu
## Part_one -- The Setup

## Part_one -- The Setup

The front end of the application uses Twitter Bootstrap for styling and layout, jQuery for client-side interactivity, PHP and CodeIgniter for most of the functionality, and MySQL for data storage. This is a fairly common toolset that runs on most L/W/M/AMP-style environment stacks. The code available on GitHub has everything you need to run the app yourself, provided you have a web server, MySQL, and PHP 5.3 or greater.

You’ll need to create a database (preferably called ‘cisock’), and then import cisock.sql in the root of the ‘partOne’ folder in the repository. You can do this with the following command from the command line (be sure to change ‘yourusername’ and ‘/path/to/’ to match your local setup):

mysql -u yourusername -p -h localhost cisock < /path/to/cisock.sql
Once you’ve gotten the code checked out into your web root and the SQL imported, you’ll need to do some slight configuration before getting started. In ‘part_one/application/config/config.php’ you will need to change line 17 to reflect your local URL. If you simply cloned the project directly into your ‘localhost’ web root, then no changes will likely be needed. A similar fix is necessary in ‘part_one/assets/js/main.js’ line 6. The context root of your application goes here. Again, if you cloned to your web root, the default value should be fine. Ideally, the context root should only have to be configured in one place, but it is what it is for now.

Secondly, the settings in ‘part_one/application/config/database.php’ must be set to reflect your local database configuration. The following entries are specific to your local environment:

$db['default']['hostname'] = 'localhost';
$db['default']['username'] = 'yourdatabaseusernamehere';
$db['default']['password'] = 'yourdatabasepasswordhere';
$db['default']['database'] = 'cisock'; //or use the database name you chose, if it is different
Once that is done, you should be able to navigate your browser to the /part_one/ directory and see the login screen.

### Database 
### Database 

username = india_dba
password = 47u|(3y=I@k

create user 'india_dba'@'localhost' identified by '47u|(3y=I@k';

GRANT ALL PRIVILEGES ON * . * TO 'india_dba'@'localhost';
FLUSH PRIVILEGES;






## Editing
 1. Editing for first commit
 2. Editing for 2nd commit
 3. Editing for 3rd commit
 4. Editing for 4th commit
 5. Editing for 5th commit
 6. Editing for 6th commit


To check webhook working 1
To check webhook working 2
To check webhook working 3
To check webhook working 4


editinggggggggggggggg
new
lkanflknf

editinggggggggggggggg
new
lkanflknf

editinggggggggggggggg
new
lkanflknf

editinggggggggggggggg
new
lkanflknf



editinggggggggggggggg
new
lkanflknf

editinggggggggggggggg
new

editinggggggggggggggg
new
lkanflknf

editinggggggggggggggg
new
lkanflkn
lkanflkn

