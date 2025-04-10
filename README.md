# gRPC-Based-Online-Shopping-System
### Remote Invocation - Online Shopping System using gRPC

Design and implement an online shopping system using gRPC, allowing interaction for two types of users: **customer** and **admin**.

#### Operations:
1. **add_product**: The admin adds a new product with details such as name, description, price, stock quantity, SKU, and status (available/out of stock). The operation returns a unique code for the product.
2. **create_users**: Create and stream multiple users (customers or admins) to the server.
3. **update_product**: The admin updates product details.
4. **remove_product**: The admin removes a product, returning the updated product list.
5. **list_available_products**: The customer retrieves a list of all available products.
6. **search_product**: The customer searches for a product by SKU.
7. **add_to_cart**: The customer adds a product to their cart.
8. **place_order**: The customer places an order for the products in their cart.

#### Deliverables:
- **Server Implementation**:  
  Implement the server using Ballerina and gRPC to handle incoming requests.
  
- **Client Implementation**:  
  Clients should be able to connect to the server, handle user input, and perform the operations.




