# **COVID19 - Testing Management System**

---

## Tools and Technology
---

Language Used - PHP

User Interface Design - HTML, JQUERY, JAVASCRIPT

Database - 	MySQL

Web Browser - Brave, Edge, Mozilla, Google Chrome, Opera etc.

Software - XAMPP / Wamp / Mamp/ Lamp (anyone)

---
## **System Functions**
---

## 1. Admin Module

    Admin is the superuser of the website who can manage everything on the website. Admin can log in through the login page.
---

- `Dashboard`

        In this section, the admin can see all detail in brief like the total, assigned and the sample collected and completed tests.

- `Worker`
        
        In this section, the admin can manage Worker (add, update, delete).

- `Testing`

        In this section, the admin can manage all the tests like assign the test to Worker and update the history.


- `Report`

        In this section, the admin can generate two types of report. One is between dates reports and another one is by search. Admin can search the report by order number, name and mobile number.


- Admin can also update his profile, change the password and recover the password.



---
``Dashboard includes:``
---

- Total test 
- Total assigned
- On the way for sample collection
- Sample collected
- Sample sent to Lab
- Report Deliverd
- Total Registered Users
- Total Registered Workers

---

![image](https://user-images.githubusercontent.com/66620521/121848147-3efa7a80-cd07-11eb-97c8-610308caba6f.png)

---

## 2. User(Patient) Module

      User can visit the application through a URL.

---

- `Testing`
        
        This section divided into two parts. One is for new user and another one is for registered user. New user(First-time user) needs to provide personal and testing Information. A registered user only needs to provide test information, their personal information will be fetched from the database.
           
- `Report`
    
        In this section, Users can search their test report using order number, name and registered mobile number.

-  `Dashboard`

        In this section, the User can see how many tests are done.

---
``Report Search:``
--

- B/w Dates Report Date Selection
---

![image](https://user-images.githubusercontent.com/66620521/121850956-2c824000-cd0b-11eb-96b7-b74bd47fefc2.png)

---
- Search By User Name or Mobile Number or Order Number
---


![image](https://user-images.githubusercontent.com/66620521/121851347-9c90c600-cd0b-11eb-9b6e-7b7f72aae3e8.png)


## **Installation Steps**
---

1. Download the zip file and Unzip the file on your local server.

2. Put this file inside "c:/xampp/htdocs/"


3. Database Configuration Open PHPMyAdmin Create a Database named `covidtmsdb`.Import database `covidtmsdb.sql` from the downloaded folder(inside the database)

4. Open Your browser put inside "http://localhost/Covid/" 

5. To Login as admin put "http://localhost/Covid/login.php"


---
## **Admin Login Details**
---

![image](https://user-images.githubusercontent.com/66620521/121851741-1b85fe80-cd0c-11eb-8784-84a94e161131.png)

- Username: princy

- Password: pc1234

![Princy's GitHub stats](https://github-readme-stats.vercel.app/api?username=PrincyChauhan&show_icons=true&theme=dark)

