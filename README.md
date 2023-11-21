# online_bookstore

Project Requirements:

1. Install mysql server on your local machine and set your hostname 'root'
2. Install Python3
3. Pycharm or any IDE

Setup Database:
1. Open terminal in your system
2. Navigate to your project directory using cd command eg. /online_bookstore
3. Execute command ls and check whether book_store.sql file is present if not navigate to sql file location in project
4. Login to mysql server command line using command:
   > mysql -u root -p
5. Next we need to create database for our project using command:
   > create database book_store;
   > exit
6. Execute command:
   > mysql -u root -p book_store < online_bookstore/book_store.sql 

Steps to run backend:

1. Open project in Pycharm or any IDE you perfer to code.
2. Open project terminal.
3. Run the following commands on your terminal:
   
   > python3 --version
   > python3 -m venv venv
   > source venv/bin/activate
   > pip3 install requirements.txt
   

