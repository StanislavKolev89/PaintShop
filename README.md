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

**Java (JRE) 17**

* <b>Windows</b> and <b>MacOS X</b> installers include JRE so just use them and don't think about internals.
* On <b>Linux</b> you may need to install Java manually (usually by running `sudo apt-get install openjdk-17-jdk` or something similar).
* If you don't use installer (on Windows or Mac OS X) you may need to download Java (JDK) from <a href="https://www.oracle.com/java/technologies/javase/jdk14-archive-downloads.html">Oracle website</a>.

**MySQL Workbench 8.0.21**

* You can download MySQL Workbench from official <a href="https://dev.mysql.com/downloads/workbench/"> MySQL Workbench website.

* If you use IntelliJ IDEA the database management functionality is supported by the Database tools and SQL plugin.

## Building

#### Prerequisites:

 1. Java (JDK) 17
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

  Simply open terminal and write the following command

  ```
   docker-compose -f docker-compose.yaml up 
   ```
  

 **Valid Profile Accounts:**

 * Admin- have the opportunity to track sales, add or remove new categories, products, second hand items,check all orders per users and give users admin rights and also edit personal information.

* User- can buy and sell items, edit personal information, edit their items for sale. 

### Routes


URLs | Description
---------|---------
*/* | Index page - page with carousel showing all available categories of products.
*/users/login* | Login page - page where user can enter login information.
*/users/register* | Register page - page where user can make registration.
*/contacts* | Contacts page - page with contact information.
*/used/products/forSale* | Used products page - page where all second hand products can be seen.
*/products/all* | New products page - page where all new products for sale can be seen.
*/admin* | Admin panel page - page with options for admin to check and edit additional information about users,products,orders and categories.
*/admin/users/all* | All users page - page where admin can see all registered users with options for deleteing ,giving or revoking admin rights.
*/admin/orders/all* |All orders page - page where admin can see all orders,their details and also remove them.
*/admin/orders/details/{id}* | Page where admin can see order details.
*/admin/products/all* | All products page - page where admin can see all new products for sale with option to delete or edit them.
*/admin/products/edit/{id}* | Page where admin can edit products info, price and category.
*/admin/categories/all* | All categories page - page where admin can see all categories with option to edit, delete them or add new one. 
*/admin/categories/edit/1* | Page where admin can edit category details.
*/users/profile* | Page where user can edit some personal information.
*/used/products/details/{id}* | Page where user can see specific details of a product.
*/users/logout* | User logout.


Database Diagram Screenshot
 ---
 
 ![database](src/main/resources/static/screenshots/database.png)
 
 
 Website Screenshots
 ---
 
 - Index Page - Without logged user

 ![indexpage](src/main/resources/static/screenshots/homeLoggedAdmin.png) 


 - Index Page - With logged user

 ![indexpage](src/main/resources/static/screenshots/homeNoLoggedUser.png)


 - Login Page 

 ![loginpage](src/main/resources/static/screenshots/loginPage.png)

- Register Page

![registerpage](src/main/resources/static/screenshots/registerPage.png)

- Contacts Page

![contactspage](src/main/resources/static/screenshots/contacts.png)
 
- Admin Panel Page

![adminpage](src/main/resources/static/screenshots/adminPanel.png)

- Admin - All users page

![adminallusers](src/main/resources/static/screenshots/adminAllUsers.png)

- Admin - All orders page

![adminallorders](src/main/resources/static/screenshots/adminAllOrders.png)

- Admin - Single order details page 

![adminOrderDetails](src/main/resources/static/screenshots/orderDetails.png)


- Admin - All products page

![adminallproducts](src/main/resources/static/screenshots/adminAllProducts.png)

- Admin - Edit product page 

![admineditProduct](src/main/resources/static/screenshots/editProduct.png)

- Admin - All categories page

![adminallusers](src/main/resources/static/screenshots/adminAllCategories.png)

-Admin - Edit category page 

![adminallusers](src/main/resources/static/screenshots/editCategory.png)

- All products page 

![allProducts](src/main/resources/static/screenshots/allProducts.png)

 ##### Products can be filtered by category

  ![allProductsCategores](src/main/resources/static/screenshots/allProductsCategories.png)


  ![allProductsClear](src/main/resources/static/screenshots/allProductsClear.png)


  ![allProductsBasecoat](src/main/resources/static/screenshots/allProductsBasecoat.png)

- Single product page 

![allProducts](src/main/resources/static/screenshots/singleProductPage.png)

##### If there are not enough items in stock a warning message appear.

![notEnoughItems](src/main/resources/static/screenshots/notEnoughItems.png)


- My profile page 

![myProfile](src/main/resources/static/screenshots/myProfile.png)

- Edit product page (User can edit or delete own products)
 
![userEditProductPage](src/main/resources/static/screenshots/editUsedProduct.png)

- Delete product page (Admin can delete other users products)

![adminDeleteProductPage](src/main/resources/static/screenshots/adminDeleteUsedProduct.png)


- Shopping cart page (User can check products in cart)

![adminDeleteProductPage](src/main/resources/static/screenshots/shoppingCart.png)


- Add comments (Users can add comments for all products)

![addcommentsone](src/main/resources/static/screenshots/commentsAddOne.png)

![addcommentstwo](src/main/resources/static/screenshots/commentsAddTwo.png)



 
