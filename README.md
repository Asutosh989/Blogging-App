# Blogging-App

This app provides a platform to build your own blog posts, edit them and also view other blog posts.

## To start the app

 - Install the required packages
    
    `pip install -r requirements.txt`
 
 - Rename `.env-example` to `.env` and make the required changes like updating the following
 
   - "MYSQL_USER" 
   
   - "MYSQL_PASSWORD"
   
 
 - To configure the required database in the MySQL Database
 
    `mysql -u <username> -p < blog.sql`
    
 - Start the app by running the following command
 
    `python app.py`
 

