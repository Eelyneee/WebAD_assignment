# Web application development assignment (Jan2021)

This is a school group assignment aim to learn:

- introduction web application development 
- HTML, CSS, JavaScript, PHP, MySQL

A online selling shoe website without include payment gateway. Further requirement listed below:

- A website for selling sport shoes.
- Have 3 types of users (Amin, Member, Guest).
- Admin and Guest websites' style will changes depends on gender
  stored in database.
- Not include payment gateway.
- Using HTML, CSS, JavaScript, PHP, MySQL.
- Any framework is not allowed to applied.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot & website explanation

- https://drive.google.com/drive/u/2/folders/1Cz82MJSvYhP4PXFWELCUvNGH-2JZEWcZ

- **Landing page, Member’s and guest login page**

  - Descriptions: Members can login into their existing account, or sign up an account before login.

  ![image-20210615080444015](img\image-20210615080444015.png)

- **Blog Page**

  - Description: When users enter a blog page, they can view all the blogs provided. If members find any interested blog, they can view the blog content by clicking on the blog title or the blog’s picture. They can also add new blog content if they have any idea by clicking on the add button on the left side of the page.
  - ![image-20210615080954288](img\image-20210615080954288.png)

- **Blog content page**

    - Description: When a member comes to the blog content, the member can view the introduction, main content, and conclusion of the blog post.
    - ![image-20210615081144419](img\image-20210615081144419.png)
    - 

  

##### **Member’s view (Women’s style)**

- **Sign Up Account Page**

  - Description: Members can sign up an account as a new member for free. After signup as members, users will be redirected to the Login page and continue login into the website to purchase shoes.
  - ![image-20210615080558442](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080558442.png)
- **Home Page**

  - Description: After members have logged into the website using their account, they will be directed to the home page(as shown in the picture above). Users can also use the search filter that is located on the left to view a list of shoes based on their favorite. 
  - ![image-20210615080644831](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080644831.png)
- **Shoe Details Page**

  - Description: After the member clicks into the selected shoe, the member will be directed to this shoe details page to view the details, rating and reviews of the shoes. If a member was interested in this shoe and willing to purchase it. The member can first choose the size he/she wants, then choose how many quantities they would like to have. After that, they can either click on the “Add to Cart” button and continue shopping or click on the “Buy” button and direct them to the cart page. 
  - ![image-20210615080710520](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080710520.png)
  - After the member clicks on the “Add to Cart” button, the system will prompt the message shown in the picture below.
  - ![image-20210615080715387](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080715387.png)
- **Shop Page**

  - Description: The picture above shows the shop page. This page will show the user what kind of shoes that they have added into the cart. Members can decide the specific size and quantity of the shoe or remove the shoe from the cart.
  - ![image-20210615080757993](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080757993.png)
  - Description: After clicking on the “Confirm” button, a total payment price will be displayed below of the shopping cart. It requires the user to fill in the recipient name, recipient phone number and recipient address. 
  - ![image-20210615080811527](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080811527.png)
  - Description: After clicking the “Checkout” button, the system will prompt out a message that is shown in the picture above.
  - ![image-20210615080826163](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080826163.png)
  - Description: The system will load back to the shopping cart page with empty items.
  - ![image-20210615080832685](C:\Users\user\Desktop\SportifySportShoeWebsite\img\image-20210615080832685.png)
- **FAQ Page**
  - Description: Members can also find and view some frequently asked questions provided by the website. 
  - ![image-20210615081240318](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081240318.png)
- **About Us Page**
  - Description: In this page, members can understand more details about “Sportify”.
  - ![image-20210615081258150](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081258150.png)
- **Contact Us Page**
  * Description: If the member has some questions, they can direct to the “Contact us” page for more information on how to contact the administrator or direct fill in the form provided to submit their inquiry to the admin.
  * ![image-20210615081321331](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081321331.png)



##### Admin view

- **Admin Login Page**
  - Description: This page is only for the administration of this website to login and make some changes inside the website. 
  - ![image-20210615081414163](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081414163.png)
  
- **Admin Home Page**
  - Descriptions: Admin home page is the same as the user home page. The difference of the admin home page is there is an edit function at bottom left for the admin to add, delete or edit shoes. 
  - ![image-20210615081442896](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081442896.png)
  
- **Add Shoe Page**
  - Description: This page is for admin to add shoes into the website.
  - ![image-20210615081505402](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081505402.png)
  
- **Delete Shoe Page** 
  
  - Description: This page is for admin to delete the existing shoes.
  - ![image-20210615081532897](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081532897.png)
  
- **Update Shoe Page** 

  - Description: The admin has to insert the shoe details ID to search whether the shoe is existing or not in order to make changes.
  - ![image-20210615081550022](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081550022.png)
  - Description: If the shoe exists in the website, the admin can update the shoe details ID, shoe ID, size, quantity and also discount.
  - ![image-20210615081607726](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081607726.png)

- **Admin Shopping Cart Page** 

  - Description: Admin is not inappropriate for Shopping Cart page. 
  - ![image-20210615081637854](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081637854.png)

- **Admin FAQ Page** 

- Description: Admins can find and view some frequently asked questions added to the website. Admins is also allowed to add,update and delete by clicking on the pen button. Admin will be redirected to admin_faq page.

- ![image-20210615081655250](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081655250.png)

-  **Admin_faq** **Page** 

  - Description: Admins can find and view some frequently asked questions added to the website. Admins is also allowed to add,update and delete by clicking on the pen button. Admin will be redirected to admin_faq page.
  - ![image-20210615081713739](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081713739.png)
  -  Description: Admin can view all the faq inserted before, delete the faq. Admin also is allowed to update faq by using id to select the question and insert new faq in this page. 
  - ![image-20210615081731312](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081731312.png)
  - ![image-20210615081737600](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081737600.png)

- **Admin About Us page** 

  - Description: : In this page, admin can understand more details about “Sportify”.
  - ![image-20210615081753728](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081753728.png)

- **Admin Contact Us Page** 

  - Description:  Admins can also find the contact details at this page like other users. Admins is also allowed to view, reply,update the enquiry sent by users by clicking on the mail button. Admin will be redirected to admin_contactUs page.
  - ![image-20210615081949510](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615081949510.png)

- **Admin_contactUs** **page** 

  - Description: In this page, admin can view 3 different status of enquiry(unread,read,replied). Admin can also update the status of the enquiry or remove the enquiry from the database. Admin also allowed to send email to answer the user’s enquiry by clicking on the particular user’s email.

  ![image-20210615082029483](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082029483.png)

##### **Guest’s view (Men’s style)**

- **Guest Login Page** 
  - Descriptions: Guests have to choose between “Men” and “Women” before clicking on the “Continue as guest” button.
  - ![image-20210615082120716](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082120716.png)
  
- **Home Page** 
  - Description: In this page, admin can view 3 different status of enquiry(unread,read,replied). Admin can also update the status of the enquiry or remove the enquiry from the database. Admin also allowed to send email to answer the user’s enquiry by clicking on the particular user’s email.
  - ![image-20210615082137479](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082137479.png)
  
- **Shoe Details Page** 
  - Description: After the guests click into the selected shoe, the guests will be directed to this shoe details page to view the details, rating and reviews of the shoes. Guests can view all the details about the particular shoe, but guests cannot add to cart.
  - ![image-20210615082159986](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082159986.png)
  - Description: If guests click on the “Add to Cart” button, the system will prompt out a message as shown above.
  - ![image-20210615082205675](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082205675.png)
  
- **Shoe page** 
  - Description: Shop page is only allowed for members, guests can only access full function of the page after login as members.
  - ![image-20210615082229531](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082229531.png)
  
- **FAQ Page** Description: 
  
  - Guests can also find and view some frequently asked questions provided by the website.
  -  ![image-20210615082302926](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082302926.png)
  
- **About Us Page**

  - Description: In this page, guests can understand more details about “Sportify”.
  - ![image-20210615082325171](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082325171.png)

  

- **Contact Us Page**
  - Description: If the guests have some questions, they can direct to the “Contact us” page for more information on how to contact the administrator or directly fill in the form provided to submit their inquiry to the admin.
  - ![image-20210615082354115](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20210615082354115.png)

  

### Links

- Solution URL:https://github.com/Eelyneee/WebAD_assignment

## My process

### Built with

- HTML
- CSS
- JavaScript
- PHP
- MySQL



### Continued development

- [ ] Redesign website
- [ ] Learn how to deploy this web app



## Authors

- Elaine Low Jing Yi
- Low Ee Lyne
- Low Jia Wei
- Wong Yuk Han
- Teh Liang Sean

### Low Ee Lyne’s workload

- Collected New Balance‘s shoe details, photos and ratings and added the data into the database.
- Developed About Us page.
- Developed header and footer for the whole website.
- Contributed one of the blog's data.
- Continue development of Login and Sign Up page validation, and complete added data into database
- Developed Login session and make sure users required to login in order to view other pages of the website(excluded blog)
- Developed logout page.
- Developed changing style of pages based on user’s gender recorded in database
- Developed shop page(=shopping cart page)
- Continued development of Contact us validation, added data to database and retrieve frequently asked questions from database
- Developed admin’s side contact us page which allows admin to view, read, and reply enquiry.
- Developed admin’s side faq page which allows admin to add, update, or delete faq.
- Contributed in video presentation (admin part).
