<img src="https://github.com/violeta-kastreva/quizzical/blob/master/quizzical/src/main/resources/static/img/logo.png?raw=true" align="right" width="50" height="50"/>

# PaintShop

**Contributor:**

*  Stanislav Kolev

**Description:**


PaintShop is basically website,based on MVC pattern, in which you can purchase and 
also sell items and write comments. 
There are two type of users:




**Technologies:**

**Front-End:**

 * HTML

 * CSS

* Bootstrap

* JavaScript

* Thymeleaf


 
**Back-End:**
*   Java
*   Spring Boot 
*   Spring MVC 
*   Spring Security
*   MySQL Database 
*   Hibernate
*   JPA

## Running

**PaintShop run requirements:**

**Java (JRE) 14**

* <b>Windows</b> and <b>MacOS X</b> installers include JRE so just use them and don't think about internals.
* On <b>Linux</b> you may need to install Java manually (usually by running `sudo apt-get install openjdk-14-jdk` or something similar).
* If you don't use installer (on Windows or Mac OS X) you may need to download Java (JDK) from <a href="https://www.oracle.com/java/technologies/javase/jdk14-archive-downloads.html">Oracle website</a>.

**MySQL Workbench 8.0.21**

* You can download MySQL Workbench from official <a href="https://dev.mysql.com/downloads/workbench/"> MySQL Workbench website.

## Building

#### Prerequisites:

 1. Java (JDK) 14 
 2. Apache Maven 3+
 3. MySQL Dialect 8
 4. Internet access
 5. Git client

#### Build
**Before build the project you need follow a few steps:**

 1. Clone GitHub Repository using the following command:
 
   ```
    $ git clone https://github.com/StanislavKolev89/PaintShop-ProjectDefence.git
   ```
 2. In application properties file you need to enter your personal database username and password:
   ```
   spring.datasource.username=[DB USERNAME]
   spring.datasource.password=[DB PASSWORD]
   ```

  Application properties file is in `src/main/resources/application.properties`

  You can also just copy docker-compose.yaml file and execute it if you have locally installed Docker

  Simply open terminal after you  and write the following command

  ```
   docker-compose -f docker-compose.yaml up 
   ```
  

 **Valid Profile Accounts:**

 * Admin- have the opportunity to track sales, add or remove new categories, products, second hand items,check all orders per users and give users admin rights and also edit personal information.

* User- can buy and sell items, edit personal information, edit their items for sale. 

### Routes


Database Diagram Screenshot
 ---
 
 ![database](src/main/resources/static/screenshots/database.png)
 
 
 Website Screenshots
 ---
 
 - Index Page- Without logged user

 ![indexpage](src/main/resources/static/screenshots/homeLoggedAdmin.png) 


 - Index Page- With logged user

 ![indexpage](src/main/resources/static/screenshots/homeNoLoggedUser.png)


 - Login Page 

 ![loginpage](src/main/resources/static/screenshots/loginPage.png)

- Register Page

![registerpage](src/main/resources/static/screenshots/registerPage.png)

- Contacts Page

![contactspage](src/main/resources/static/screenshots/contacts.png)
 
- Admin Panel Page

![adminpage](src/main/resources/static/screenshots/adminPanel.png)

- Admin- All Users Page

![adminallusers](src/main/resources/static/screenshots/adminAllUsers.png)

- Admin- All Orders Page

![adminallorders](src/main/resources/static/screenshots/adminAllOrders.png)


- Admin- All Products Page

![adminallproducts](src/main/resources/static/screenshots/adminAllProducts.png)


- Admin- All Categories Page

![adminallusers](src/main/resources/static/screenshots/adminAllCategories.png)

-My Profile Page 

![myProfile](src/main/resources/static/screenshots/myProfile.png)

-Edit Product Page (User can edit or delete own products)
 
![userEditProductPage](src/main/resources/static/screenshots/editUsedProduct.png)

-Delete Product Page (Admin can delete other users products)

![adminDeleteProductPage](src/main/resources/static/screenshots/adminDeleteUsedProduct.png)


-Shopping cart Page (User can check products in cart)

![adminDeleteProductPage](src/main/resources/static/screenshots/shoppingCart.png)


 
