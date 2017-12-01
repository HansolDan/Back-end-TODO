# Change Log
Team membership: Hansol Lee(Captain), Daniel Capacio (Mate)  
Team conventions: Allman notation  
Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  
Additions: Newest last  
Date format: YYYY-MM-DD

## 2017-11-30 : Backend  
-  Deleted all controllers except Welcome.
-  Simplified the base Welcome.php
-  Removed all the other PHP files in the views folder, except homepage.php
-  Deleted unit test
-  Cleaned up MY_Controller
-  Replaced the contents of views/homepage.php with a message to the effect that this is a server webapp.
-  Modified controllers/Welcome to display the modified homepage view.
-  Installed the package-restful package from the Jedi Academy.
-  Edit config/autoload. 
-  Added Job.php (RESTful controller)
-  Add CRUD method in Job.php
-  Change Tasks.php to extends CSV_Model
