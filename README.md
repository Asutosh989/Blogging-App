# Blogging-App

This app provides a platform to build your own Blogs, edit them and also view other blogs.

## How to Run the Project

### Installing Required Packages
 - This project requires the installation of third-party libraries. We'll be using `pip` to install those required packages.
 - To install `pip`, enter:
   `sudo apt-get -qqy install python-pip`.
 
 - Next, we'll install the required packages provided in `requirements.txt` by running:
   `sudo pip install -r requirements.txt`

### Updating the Database 
 - Rename `.env-example` to `.env` and make the required changes like updating the following
 
   - "MYSQL_USER" 
   
   - "MYSQL_PASSWORD"
   
 
 - To configure the required database in the MySQL Database
 
    `mysql -u <username> -p < blog.sql`
    
### Running the Application 
- Start the app by running
 
    `python app.py`
 

