Group Members: Hashim Shah, Riya Jain, Prajjwal Singhal, Priyanshi Jajoo, Rene Figueroa, Manasa Hari

Purpose:
To build a Virtual Private Network Management System database. This database stores users’ personal information such as SSN, full name, address, billing information and also keeps tracks of VPN servers information such as locations and protocols. 

Database Details:
We used MySQL as our Database Engine and used HTML and CSS as our application technologies. The framework for our project was Node.js and the language was Javascript. We used a simple graphical user interface that is hosted on AWS.

Figure 1: VPN Management System Development Stack diagram

Figure 2: Architecture Diagram for the VPN Provider Management System

The final list of functionalities/operations:
There is a user in our VPN management system where the users can enroll in a membership plan and can also add or remove devices, but the total number of devices can never exceed five to the company’s VPN. The user can also view the information regarding the devices and the membership plan that they have enrolled in. 
Further, our database stores the information of a regular employee who will monitor the status of the server and report the same to the server admin. The server admin manages multiple servers and can add or remove switches to a server as needed. Also, a server admin supervises regular employee and takes an action if the server is found to be bad. 

VPN Management System
# Set Up application in your local
* open terminal and run the following commands
1. git clone this project
2. cd project
3. git pull origin master

# Database Connection
1. db_config contains the mysql connection string.
2. create database named 'vpn_management' in your local mysql instance.
3. Update this string in db_config file {host: "localhost",user: "your_username",password: "*******",database:"vpn_management"}

# Running the App
1. npm i
2. node app.js or nodemon app.js or npm start

# Web Browser
 go to the browser and enter localhost:9000
