# Create SQL queries with the clauses below:

- Simple recoveries with SELECT Statement
- Filters with WHERE Statement
- Create expressions to generate derived attributes
- Set data ordering with ORDER BY
- Filter conditions for groups - HAVING Statement
- Create joins between tables to provide a more complex perspective on the data

# Objective:
“Refine the presented model by adding the following points”
- PJ and PF client – ​​An account can be PJ or PF, but cannot have both information;
- Payment – ​​You may have registered more than one payment method;
- Delivery - Has status and tracking code;
- Some of the questions you can ask to support SQL queries:
- How many orders were placed by each customer?
- Are any vendors also a supplier?
- Product and supplier relationship
- Product and stock relationship;
- List of supplier names and product names;

# Additional questions to be answered with the queries:
- What is the total value of sales with these customers? It must contain: Customer Name, Product Name, Purchased Quantity, Unit and Total Price, Order Status, Digital Wallet Number and Digital Wallet Balance. Sort by, Order status, customer name and total purchase amount;
- How many registered customers?
- How many registered products with a price greater than 500 reais?
- Show the name and price of products with a price greater than 1000 reais
- Relationship of Customer Name, CPF with the digital wallet number
- List of Customer Name, CPF with the digital wallet number of accounts with a balance greater than 500 reais
- Relation of the Product Name with the quantity in stock, returning only those that have less than 100 products in stock for replacement;
- What is the value in reais of each product in stock and the value of the stock?
- What is the total value in reais of the stock?
- Which company is responsible for delivering each order, customer name and delivery address?


# Contestualizing the Logical Model based on the Constructed Conceptual

## E-commerce Database Project

- Context: Requirements gathering
- Conceptual Project: Entity Relationship Model
- Logical Design: Relational Model

## Modeling E-COMMERCE:
- Product:
- Products are sold through a single online platform. However, these may have different sellers (third parties)
- Each product has a supplier
- One or more products can compose the order

- Client:
- Customers can register on the site with their CPF or CNPJ
- The customer's address will determine the shipping cost
- A customer can buy more than one order. This has a grace period for returning the product.

- Request:
- Orders are created by customers and have purchase information, address and delivery status
- One or more products make up the order
- The order can be canceled

## Refinement:
- PJ and PF client - An account can be PJ or PF, but cannot have both information
- Payment - You may have registered more than one payment method
- Delivery - has status and restriction code
- Added more items that I thought were interesting to bring the project closer to reality

### Software used for modeling
**MySQL Workbench**

# In English
# Create SQL queries with the clauses below:

- Simple recoveries with SELECT Statement
- Filters with WHERE Declaration
- Create expressions to generate result attributes
- Set data ordering with ORDER BY
- Filter conditions for groups - HAVING Declaration
- Create joins between tables to provide a more complex perspective on the data