# SQL-Learning-Tutorial

The purpose of this repository is to serve as a practical study guide for SQL learners and a cheat sheet for future use. The Database Management System of Choice was PostgreSQL due to its open-source and multi-OS characteristics.

## 1. Contents

  - DVD_practice: PostgreSQL Script with SQL coding excercises.
  - dvdrental.tar: .tar file used to backup the database schema and data into PgAdmin.
  - PostgreSQL-Sample-Database.png: Entity Relationship Diagram for reference.

## 2. Installation

The installation steps are as follows:

  ### 2.1 Install PostgreSQL (SQL Engine):

   - Go to: https://www.postgresql.org/download/
   - Select your Operating System.
   - Click on "Download the Installer".
   - Click on the program version that corresponds to you OS.
   - Save the prompted file into the folder of your preference.
   - Unzip the downloaded file and access the installer.
   - Follow the installer's instructions. Generally the pre-selected default options are enough to get started. Make sure you document the selected password     defined through the installer as those credentials are required to access PgAdmin and databases. If you ever forget the password you will need to uninstall PostgreSQL and repreat the process.
   - If you get an error at the end of the installation wizard related to database cluster initialization it is probably because you need to download an older version of PostgreSQL.
    
  ### 2.2 Install PgAdmin (Graphical User Interface)
  
   - Go to: https://www.pgadmin.org/download/
   - Select your Operating System inside the version of PgAdmin you want to download.
   - Select the latest release of the version.
   - Select the download file (generally the .dmg file in MacOS and the .exe file on Windows).
   - Save the file into the folder of your preference.
   - Once the file has been downloaded click on it to run the installer.
   - Follow the installer's instructions.
   - When the installation is complete define the location for the PgAdmin app.

  ### 2.3 Restore the .tar file into PgAdmin:
  
   - Download the "dvdrental.tar" file. Do not attempt to open it or unzip it.
   - Restart your device.
   - Start PgAdmin.
   - Set a master password to access PgAdmin (this is a different password from the one you defined when installing PostgreSQL, but you can set the same one if prefered).
   - Open the server dropdown.
   - Select the version of PostgreSQL.
   - Provide your access credential (password that was set up when PostgreSQL was installed).
   - Under the PostgreSQL dropdown, right-click on databases and then select Create -> Database.
   - On the "General" tab define a name for the database.
   - Click on "Save".
   - Click on the created database to activate the connection to it.
   - Right-click on the created database and select "Restore".
   - On the "General" tab provide the download path to the .tar file inside the "Filename" input box.
   - On the "Restore Options" tab turn the "Pre-Data", "Data" and "Post-Data toggles to "Yes".
   - Select "Restore" to conclude the process.
   - Note: You can ignore the "Failed (exit code: 1)" error if it comes up.
   - Right-click on the new database and select "Refresh" to make the recent changes appear.

  ### 2.4 Run your first Query:
  
   - Right-click on the created database and select "Query Tool".
   - Inside the "Query Tool" tab is where you can perform any queries to retrieve data from the database.
   - To open the "DVD_practice" script to use as reference for your own learning, click on the folder icon at the top left corner of the query tool.
   - Select the file path to the "DVD_practice" file.

## 3. Usage


## 4. Credits

Resources used to build this repository include:

  - Udemy: "The Complete SQL Bootcamp 2022: Go from Zero to Hero" by Jose Portilla (https://www.udemy.com/course/the-complete-sql-bootcamp/).
  - W3 Schools: SQL Tutorial (https://www.w3schools.com/sql/).

## 5. License

![image](https://user-images.githubusercontent.com/60116541/142733137-9ed23afb-0ee8-468e-b0f0-f90f60e70f3c.png)

This work is licensed under a Creative Commons Attribution 3.0 International License
