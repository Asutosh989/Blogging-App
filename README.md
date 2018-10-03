# Blogging-App

This app provides a platform to build your own blog posts, edit them and also view other blog posts.

## How to Run the Project

### Installing Required Packages
 - This project requires the installation of third-party libraries. We'll be using `pip` to install those required packages.
 - To install `pip`, enter:
   `sudo apt-get -qqy install python-pip`.
 
 - Next, we'll install the required packages provided in `requirements.txt` by running:
   `sudo pip install -r requirements.txt`

### Updating the Database 
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
    

### Running the Application 
- Start the app by running the following command

 
    `python app.py`
 - Rename `.env-example` to `.env` and make the required changes like updating the following
 
   - "MYSQL_USER" 
   
   - "MYSQL_PASSWORD"

