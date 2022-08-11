# Vision # 

Our vision for this application is to help small business owners and individuals to prosper and expand within this extremly hard market that is out there nowadays,
this will be a platform without being bias to any huge coopreations and will try to make everyones business a successful business hopefuly. If your are looking for
a product that is customly made for you with cheap prices and giving different ideas and unique item, this application is for you.

# Scope (In/Out) #

**IN** 

- The web app will provide information to the users about all the different items and the ability to search for a specific item.
- The web app will provide the ability to present your data (items) for potential buyers.
- Users will be able to buy their selected items.
- Users will be able to see how many times their items was viewed
- Each item will have a comment section for users to write their reviews

**OUT**

- The web app will not be able to prcess any purchasement
- The website will never turn into an IOS or Android app

## Minimum Viable Product vs Strech ##

our minimum viable product is that our App will be a place where anyone can share their items freely and it will be ensured that it is only specified for new small businesses and upcoming handcrafts for individuals, and our strech goal is to make it a huge platform where even big corporates can place their products as well.

# Functional Requirements #

- An admin can create and delete user accounts
- A user can update their profile information
- A user can search all of the products in the inventory
- A user can add products
- A user can review other peoples products

## Data Flow ##

When the user enters the aplication he will see a home page with the ability to browse product, if he wants to engage, he has to sign up and submit his informations which will be a request to the server and the server will handle the data and save it to the database, meanwhile, the user will have a profile page where he can edit his info and all of this will have the same data flow as before, then he will be able to add a new product which will use the Create method and send this data to the database through the server, then he can go to the homepage again and search(filter) to any item he wants, he will have the ability to add items to cart which will send the selected data to a unique database for the user and save the items in a special list for the user to review later. When the user is done, he can simply sign out.

# Non-Functional Requirements #

1. Security: our application will be secure for users as they will be verified and authenticated before logging in.
2. Data integrity: all the items in the website will be and must be handmade by the users, they will have a copy right to their items.
3. Extensibility: the web application will be available for future development because there are many features that could be added later such as the ability to have collections and recommended items in the profile page, there also could be buttons for users to connect them with each other and discuss items and prices privetly.
