# Blogging-App

This app provides a platform to build your own Blogs, edit them and also view other blogs.

## To start the app

 - Install the required packages
    
    `pip install -r requirements.txt`
 
 - Rename `.env-example` to `.env` and make the required changes like updating the following
   ````javascript
     MYSQL_HOST = 'localhost'
     MYSQL_USER = 'MYSQL user'  <- Change username to access database
     MYSQL_PASSWORD = '12345'   <- Change password
     MYSQL_DB = 'blog'
     MYSQL_CURSORCLASS = 'DictCursor' 
   ````
   
 
 - To configure the required database in the MySQL Database
 
    `mysql -u <username> -p < blog.sql`
    
 - Start the app by running
 
    `python app.py`
 

