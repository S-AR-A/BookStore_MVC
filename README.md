# Book Store
This is a basic Web app for learning and practicing ASP.NET, MVC architecture, scaffolding, migrations in Entity Framework, etc.

# Features
* CRUD operations for books
* Cart(with sessions)
* Place Orders
* Checkout page
  
# Database
The tables are as follows:
* Books
* OrderItems 
* Orders tables

# Models 
Beside those correlated with DB tables, there are the following models:
* BookListViewModel(for filtering books)
* CartItem 

# Controllers
* Home
* Books
* Orders
* Cart
* Checkout

# Views
Shared and specific views related to controller actions.

# Migrations
Three migrations so far:
1. Initialization
2. Renamed two columns in Book model and correlated DB table
3. Added address to Order


