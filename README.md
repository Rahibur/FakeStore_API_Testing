**API Testing Report**

**Project Name: Fake Store API (<https://fakestoreapi.com/> )**

**Test Summary Link: [Click here to view**](https://chatgpt.com/c/67e900ad-f3ac-800c-9c3d-7d3687ed1653)**

**For further information, feel free to contact me:
Website: [www.rahiburrahman.com](http://www.rahiburrahman.com/)
LinkedIn: [Rahibur Rahman**](https://www.linkedin.com/in/rahibur-rahman-2158a4241/)**

-----
**Overview**

Fake Store API is a free online REST API designed to provide pseudo-real data for e-commerce or shopping websites. It is particularly useful for scenarios such as:

- Teaching purposes
- Creating sample codes
- Conducting tests
- Other scenarios requiring mock data without the need to run server-side code

This versatile tool supports a wide range of e-commerce functionalities and is widely used for learning and testing purposes. As for testing perpous ,I performed comprehensive API testing using Postman.

-----
Testing Scope

The testing focused on four main resources commonly required in e-commerce prototypes:

1. Products
1. Carts
1. Users
1. Login Token

Each resource was tested for key CRUD (Create, Read, Update, Delete) operations to ensure the API’s reliability, functionality, and consistency.

-----
**API Endpoints and Methods**

**1. Products**

The product endpoints allow for managing product details and include the following operations:

- Get All Products:
  URL: <https://fakestoreapi.com/products> 
  Method: GET
- Create a Product:
  URL: <https://fakestoreapi.com/products> 
  Method: POST
- Get a Single Product:
  URL: [https://fakestoreapi.com/products/{id}](https://fakestoreapi.com/products/%7bid%7d) 
  Method: GET
- Update a Product:
  URL: [https://fakestoreapi.com/products/{id}](https://fakestoreapi.com/products/%7bid%7d) 
  Method: POST
- Delete a Product:
  URL: [https://fakestoreapi.com/products/{id}](https://fakestoreapi.com/products/%7bid%7d) 
  Method: DELETE
-----
2\. Carts

Cart endpoints support the management of user carts and include:

- Get All Carts:
  URL: <https://fakestoreapi.com/carts> 
  Method: GET
- Create a Cart:
  URL: <https://fakestoreapi.com/carts> 
  Method: POST
- Get a Single Cart:
  URL: [https://fakestoreapi.com/carts/{id}](https://fakestoreapi.com/carts/%7bid%7d) 
  Method: GET
- Update a Cart:
  URL: [https://fakestoreapi.com/carts/{id}](https://fakestoreapi.com/carts/%7bid%7d) 
  Method: POST
- Delete a Cart:
  URL: [https://fakestoreapi.com/carts/{id}](https://fakestoreapi.com/carts/%7bid%7d) 
  Method: DELETE
-----
3\. Users

User management endpoints include the following operations:

- Get All Users:
  URL: <https://fakestoreapi.com/users> 
  Method: GET
- Create a User:
  URL: <https://fakestoreapi.com/users> 
  Method: POST
- Get a Single User:
  URL: [https://fakestoreapi.com/users/{id}](https://fakestoreapi.com/users/%7bid%7d) 
  Method: GET
- Update a User:
  URL: [https://fakestoreapi.com/users/{id}](https://fakestoreapi.com/users/%7bid%7d) 
  Method: POST
- Delete a User:
  URL: [https://fakestoreapi.com/users/{id}](https://fakestoreapi.com/users/%7bid%7d) 
  Method: DELETE
-----
4\. Login Token

The API supports login functionality for authentication via:

- Login:
  URL: <https://fakestoreapi.com/auth/login> 
  Method: POST
-----
Test Environment

The API testing was conducted using:

- Tool: Postman
- Report Generation: Newman
-----
Test Execution

The API endpoints were thoroughly tested to validate the following aspects:

- Response Status Codes: Ensuring correct HTTP status codes are returned for each operation (e.g., 200 for success, 404 for not found, etc.).
- Data Accuracy: Verifying the data returned from the endpoints matches the expected schema and values.
- Error Handling: Checking the API’s ability to handle incorrect inputs gracefully.
- Performance: Measuring the response time of the endpoints to ensure efficient operation.
-----
Conclusion

The Fake Store API provides a robust platform for developers to simulate and test e-commerce functionalities.  API testing has confirmed the reliability and usability of the provided endpoints, ensuring a seamless experience for users integrating this API into their applications.

For additional details or a walkthrough of the testing process, feel free to contact me.

-----

