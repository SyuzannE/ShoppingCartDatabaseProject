# Online Shopping Cart Database Project

## Overview  
This project is an **Online Shopping Cart Database System**, designed to provide a comprehensive solution for managing user registrations, product searches, shopping cart functionalities, order processing, and delivery address selection. The application integrates **PostgreSQL** for database management and **Java** for GUI development.  

This course project demonstrates practical implementation of database concepts and object-oriented programming techniques while emphasizing user-friendly interface design.  

## Features  
- **User Management**:  
  - Register new users.  
  - Login functionality with secure user credentials.  

- **Product Management**:  
  - Search for products using filters like name, brand, or type.  
  - Save selected products to the shopping cart.  

- **Order Processing**:  
  - Create and view orders from the shopping cart.  
  - Add and select delivery addresses.  
  - Payment integration via credit or debit card.  

- **Database Management**:  
  - Create tables and relationships for the entities (e.g., User, Product, Order).  
  - Insert, modify, and retrieve data efficiently using SQL scripts.  

## Database Structure  
### Entities:  
1. **User**: Contains user information such as name and phone number.  
2. **Buyer**: Subclass of User.  
3. **Seller**: Subclass of User.  
4. **Bank Card**: Stores credit or debit card details.  
5. **Store**: Represents sellers’ stores.  
6. **Product**: Includes details like brand, price, and customer reviews.  
7. **Order Item**: Tracks individual items in an order.  
8. **Order**: Manages overall order information.  
9. **Address**: Stores user delivery addresses.  

### Relationships:  
- **Manage**: Links Sellers to Stores.  
- **Save to Shopping Cart**: Connects Buyers with Products.  
- **Contain**: Tracks Order Items in an Order.  
- **Deliver To**: Associates Orders with Addresses.  
- **Payment**: Links Orders with Bank Cards.  

## File Descriptions  
1. **Table.sql**: Script to create tables and define relationships.  
2. **Insert.sql**: Script to populate tables with sample data.  
3. **Modification.sql**: Script to modify or update data in tables.  
4. **Java_GUI**: Contains Java files for GUI components:  
   - `MainFrame.java`: Main menu for navigating application features.  
   - `Register.java`: User registration interface.  
   - `Login.java`: Login functionality.  
   - `SearchFrame.java`: Product search page.  
   - `SaveToCartFrame.java`: Shopping cart management.  
   - `SetUpOrderFrame.java`: Create orders from the shopping cart.  
   - `AddressFrame.java`: Manage delivery addresses and finalize orders.  

## Technologies Used  
- **Java**: GUI and application logic.  
- **PostgreSQL**: Relational database for managing entities and relationships.  
- **JDBC**: Database connectivity.  

## Getting Started  
1. **Set up the database**:  
   - Run `Table.sql` to create database tables.  
   - Use `Insert.sql` to populate the tables with sample data.  

2. **Run the application**:  
   - Compile and run Java files in the `Java_GUI` directory.  
   - Follow the interfaces to register users, search products, and manage orders.  

## Future Enhancements  
- Integration of payment gateways for live transactions.  
- Enhanced product filtering and sorting options.  
- Improved UI/UX with modern design principles.  

## License  
This project is for educational purposes and follows [MIT License](LICENSE).  

---

Would you like me to modify or expand this further?
