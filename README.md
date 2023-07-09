Our main aim was to design such a book store where customer can visit our site anytime 
of the day from anywhere to view the available books, choose any of them and can order by 
paying online or can opt for cash on delivery as well. The administrator will regularly add any 
new books available to them for sale. With the help of an online book store marketplace, users 
can simply make their accounts on the particular apps they want to use. By applying filters and 
entering the author of the book they are looking for or a keyword, they get a variety of 
suggestions. The administrator will take books from the reputed publishers and vendors only.

### This project has the following functionalities:

#### 1) A Home page with product catalog
This is the page where the user will be navigated after a successful login. It will display all the
book categories and will have a search keyword option to search for the required book. It also
includes some special sections like recommended titles, weekly special books.

#### 2) Book Description
If the user would like to know details about a book he can click on the title from where he
will be directed to a Book description page. It includes the notes on the book content and also
a link to Amazon.com to get the book review.

#### 3) Shopping Cart
The user can manage a shopping cart which will include all the books he selected. The user
can edit, delete and update his shopping cart. A final shopping cart summary is displayed
which includes all the items the user selected and the final total cost.

#### 4) Managing user accounts
Each user should have an account to access all the functionalities of website. User can login
using login page and logout using the logout page. All the user sessions will be saved in the
database.

#### 5) Administration
The Administrator will be provided with special functionalities like
• Add or delete a book category
• Update Book Prices
• Add or delete data of members. 

### Architecture Design
When we run the Online Book Store Website first home page is displayed. The user
and Admin will have different rights.
#### 3.1 User Login

If you are a new user you can register using the register link or if you are already a user you
can login to purchase book and pay using the checkout. 
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/a2b75c16-2017-4ed9-aca7-1e958ce3ce6c)

##### Fig. Sign Up
A user should enter all the required fields information. If he didn’t fill all the fields he cannot
create an account. After entering all the required data click the submit button to register. Now
you can login to the Website. Login page is used to login to the website. Login page will
appear as below.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/7420f9a8-a1bc-4790-810e-df9d0b225601)

##### Fig. Sign In Page
After Successful signing up user will land to home page of the website .
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/4cef7aa7-4493-4c82-aa1c-9693b9fd6731)

##### Fig. Homepage
If you want to update your account details click Profile tab from the navigation and you will be
directed to the Profile page.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/1c3c2a9e-e435-4493-b133-aeef182e7ada)

##### Fig. Profile Page
In the update page user can change his account information and click update. The updated
information will be saved in the database.
Below image shows the details of the user’s credentials stored in the firebase account . It
securely stores the credentials of the verified logged in user in the bookshop .
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/89940381-de74-4c99-86aa-a616ef41cc3c)

##### Fig. Firebase Authentication

#### 3.2 Book Search
The user is able to search the books Category Wise. Various Category of Books are available
in the bookshop.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/46d691b9-7bb6-4ecb-8ba4-6eb5a4b7b25b)

##### Fig. Books in different Catalog

#### 3.3 Add to shopping cart
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/9a86af50-90f1-48e5-9574-265e36d67885)

##### Fig. Cart Page
After adding to the shopping cart if the user wants to continue shopping he should click the
confirm order button else he can checkout using the checkout link.
After entering the card details click the submit button to process the order.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/85ed1384-349a-4a9f-b52c-3f14e9bccbb8)

##### Fig. Payment Page

#### 3.4 Administrator

Administrator has the right to add his own books which will be visible in his own profile
page as my listings.
Below image shows the sample listings of the books.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/529a5bd4-f4b9-4957-854c-a0a051a10688)

##### Fig. Books Added
Administrator can add books using Add Products Page and providing information to the
required fields to add the books as shown below.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/973ef9d0-0357-4a95-bb13-80d9bf6ac2bc)

##### Fig. Add Books
 User can also edit the information , price and other details.
![image](https://github.com/Akhilesh020207/BookShop-Website/assets/116174735/6c039065-908a-407b-8dc7-15563527d87f)

##### Fig. Edit Product

-*-*-*-*-*-*-*-*-*-*-**-*-*-*-*-*-*-*-*-*-
