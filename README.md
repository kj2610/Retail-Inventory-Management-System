# 🍵 The Central Perk Cafe

The Central Perk Cafe is a retail management system (RMS) that handles basic cafe operations efficiently.
                                          
  ## Bill Generation
                                          
![image](https://github.com/kj2610/The-Central-Perk-Cafe/assets/112064595/53ee1f8c-c87e-4a68-ac89-6199bbd6f229)


## Features/Functions
- Admin/user sign in system using JWT authentication
- Forgot password and user verification mailing system using Spring Mailer
- Dashboard: displays summary of the categories, products, and bills
- CRUD operations to manage categories, products, bills, and staff
- Create and edit categories and products
- Create customer orders and download them as a PDF bill
- Create, download, and delete bills

All the APIs call will be done through POSTMAN and saved to corresponding tables in the SQL database. Error handling is implemented in the backend and all unauthorized access will be managed by the Admin.

## Tech Stack                                                                                                          
Backend: Spring Boot/Java                                                                                                                                   
Database: SQL

Tools Used: IntelliJ Idea, POSTMAN(APIs calls)

## Configuration and SetUP

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine. 
- Open the project in your prefered JAVA code editor.
- Open application.properties from /backend/src/main/java/resources/application.properties.
- Add DataBase URL.
- Provide DataBase Username and passWord.
- For Simple Mail Transfer Protocol(SMTP) use personal email-id and passWord.

```
DB_URL = 
PORT = 8081
SMTP_HOST = 
SMTP_PORT = 587
SMTP_USER = 
SMTP_PASS = 

```

- Change the location of Bills In your system from /backend/src/main/java/com.cafe.com.cafe/constants/CafeConstants provided path as STORE_LOCATION



