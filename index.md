## Project Description

The **Farmer Customer Connect** is an web application built using React JS, MongoDB, Node-JS and Express. Usually these technologies are referred as MERN Stack technologies. This web application is an E-Commerce website which can be used to buy organic and natural products directly from the farmers. In this Web application farmers can register themselves and sell their products at a nominal price. Customers can buy various vegetables, dairy products, and fruits from their home for a nominal price. This Web application connects both farmer’s and customer’s digitally making it easier for farmer’s to sell their products at ease without any intermediaries. This Web application is mainly aims to remove the middlemen so that the farmer’s can sell their products at a suitable price.

## Problem statement

Farmer's are facing huge losses because of the middlemen. They couldn't be able to find the better price for their crops at markets and raithu bazar. Inorder to avoid the interfernece of the middlemen farmers need a digital space to sell their crops directly to the customer. Customers can also enjoy the natural products at affordable prices if there are no middlemen. **Farmer customer connect** web application provides a digital space for the customers and farmers.

## Technologies used

* **Frontend :** React JS
* **Backend :** Node JS, Express JS and Mongo DB
* **Testing Tools :** JEST  
* **Code Versioning Systems:** Git and GitHub  
  

## Sprint 1:

* We have learned about the SCRUM methodology and various attibutes and aspects in SCRUM 
* Later, we decided on what technologies we had to use to implement this Web application
* We have decided to work on MERN technolgies. Further, we worked on basics of these MERN technologies
* In addition to that, we have learnt how to create user stories along with creation of branches in the GitHub Website
* We have worked on the MERN and created a simple Signin page which takes the details from the user and stores it in the database

## Sprint 2:

* We started working on a User story to implement the “SignIn/SignUp/SignOut” page for farmer and customer. 
* We have created the fronted i.e. UI using the React JS. later used Express, Node to create a backend and we were using MongoDB as a database to store the data from the user
* The user should give his First Name, Last Name, Email Address, Password to Sign-up to the web application in order to see his profile
* We tried to implement the Google Authentication also but we have faced issues related to the database, so we worked on the traditional way of signing up process
* We have created the Sign-in page where the user can give his details like Email Address and Password to get access to his account
* After signing in he can also Sign-out from the website using the Sign-out option

## Sprint 3:

* We have completed the basic Sign-in/Sign-up/Sign-out process. Later, we have integrated all the signin and signup pages which were made separately from the beginning 
* We have implement JWT system to our Sign-in/Sign-up process where a token is generated everytime when a user login’s to the application
* After the user has signout of the page he will not any access to the previous pages when he clicks on the back button
* We have worked on the JEST to test application we have built until now. Additionally, we have updated some of the user stories along with acceptance criteria


## Sprint 4:

* Started Implementing a new user story i.e. product display page for the Customers
* Assigned roles in the Sign-up process i.e. farmer or customer
* Designed a product page for the customer and farmer. We have designed a product page where only farmer can add products
* Resolved some bugs that came up while signing out and assigned an api for the Sign-out
* Integrated the product page with Sign-in page such that after Sign-in, page will be redirected to the products page 


## Sprint 5:
* Started testing the application using JEST
* Wrote test cases for the Signin and Sign Up page which are used by Farmer and Customer
* Wrote around 11 test cases for both Signin and Sign up process
* Pushed the files that were created until now into the github
* Decided & started integrating the code with the other team

## Sprint 6:
* Started Integration for the entire work done till now
* Got some errors while integrating such as image display error
* We have resolved image errors and we have integrated the product adding, editing and display page with signin and signout
* While signing out we got TypeError
* Decided to implement and move further with new user stories such as add to cart
