## FUNCTIONAL REQUIREMENTS
### ORDERS
| ID | Requirement |
| :-------------: | :----------: |
| FR1 | customer shall be able to filter orders. |
| FR2 | customer shall be able to rate ordered product. |
| FR3 |  customer shall be able to check the order status. |
| FR4 | customer can add profile to whom the product bought for. |
| FR5 | The system shall update the inventory data for a shipping purchase order.|

### CART
| ID | Requirement |
| :-------------: | :----------: |
| FR6 |  product shall be deleted when user clicks on remove item on cart. |
| FR7 |  user shall be able to increase the quantity of products they want to buy. |
| FR8 | guest user shall be able to place order from cart. |
| FR9 | customer shall be able to change the delivery address. |
| FR10 | customer shall be able to use the promo code when clicks on apply coupon. |

### USER
| ID | Requirement |
| :-------------: | :----------: |
| FR11 | only admin and employees shall have access to the internal database. |
| FR12 | admin shall organise and adjust the products information. |
| FR13 |  admin shall update the information of user and manage to login and check the order history. |
| FR14 |  admin shall sell gift cards to user which could be redeemed in future. |
| FR15 |  shipping charges and product removal from the cart shall be done by admin  |

### CUSTOMER
| ID | Requirement |
| :-------------: | :----------: |
| FR16 | upon browsing product details customer shall receive the product catalogue . |
| FR17 | customer shall experience minimal load time period and improved accessibility. |
| FR18 | customers shall have an option for guest account user to checkout. |
| FR19 |  progress stage shall be displayed during the customer purchase process. |
| FR20 | during final checkout process customer shall get to edit wrongly entered information. |

### PAYMENT
| ID | Requirement |
| :-------------: | :----------: |
| FR21 | Website shall be integrated with stripe payment solutions. |
| FR22 |  The system shall be accurate with transaction data. |
| FR23 |  user shall be redirected to unauthenticated landing page when he clicked on logout button. |
| FR24 | customer shall be able to use different payment methods like debit/credit, PayPal. |
| FR25 | After successful payment user shall be able to get the invoice. |


## NON-FUNDAMENTALS OF REQUIREMENTS
### SECURITY
| ID | Requirement |
| :-------------: | :----------: |
| NFR1 | privacy of customer information shall be maintained. |
| NFR2 | customer shall be provided guidelines for strong password generation. |
| NFR3 | After a period of inactivity customer shall be logged out. |
| NFR4 | customer password shall always be encrypted while using web browser. |
| NFR5 | when new password is generated customer shall authenticate again. |

### USABILITY
| ID | Requirement |
| :-------------: | :----------: |
| NFR6 | customer shall get the product quickly what he is searching for. |
| NFR7 |  categories of product should be shown to the user.|
| NFR8 | product suggestions shall be provided to the user. |
| NFR9 | user guidelines should be provided. |
| NFR10 |page should navigate to user desired product.|

### MAINTENANCE
| ID | Requirement |
| :-------------: | :----------: |
| NFR11 | customer data should be maintained. |
| NFR12 | bugs in the present version shall be fixed in the new version. |
| NFR13 | server crash when high traffic should be maintained. |
| NFR14 | when site is not responding customer shall reload the site. |
| NFR15 | cache should be cleared to reduce load time. |

### SCALABILITY
| ID | Requirement |
| :-------------: | :----------: |
| NFR16 | additional server shall be implemented upon higher order volume. |
| NFR17 | site should be able to sell multiple brands. |
| NFR18 | load time shall be minimalised by implementing lazy loading. |
| NFR19 |  gift coupons shall be provided to the customers who buys more products. |
| NFR20 | interactive home page shall be maintained. |

### PERFORMANCE
| ID | Requirement |
| :-------------: | :----------: |
| NFR21 | when there is higher spike of orders site should be reliable. |
| NFR22 | Precise and up-to-date product information and image shall be maintained. |
| NFR23 |  steady performance shall be attained with user friendly interface and less optimised images. |
| NFR24 | simple and minimal checkout flow shall be maintained for better user experience. |
| NFR25 |  Periodical updates shall result in bug fixing and better performance. |


##CHANGE MANAGEMENT PLAN

### Guidelines for the adoption of the Alpha WEB Ecommerce Application.

This document provides guidelines for the integration of the E-commerce Web application into a small business environment.

Business in the modern day is being done without the presence of a vendor and the customer in the same place. Most of the sales are done online through websites where the customers can access any store with their fingertips. Gone are the days of traveling to a shopping center to view and purchase a product. Especially with the impact of a pandemic like COVID 19. Customers are preferring to shop online in the comfort of their homes. And businesses that do not have an online presence are losing the market share of customers.
Scope: This eCommerce application acts as a template for business that wants to integrate their business online and can expand their customer base. This will not only improve sales but also the user base. Having an alternative way to access a business is always beneficial as the sales can keep happening even if the other location is down. Customers can access the site 24/7.

To run and maintain the Website a computer engineer is required. The engineer shall be trained to use the application and basic maintenance operations will be taught. A well-documented pdf that provides a step-by-step description of application usage shall be provided. 

#### The documents shall cover the following topics:
•	Creating a customer profile and how to set an ideal password.
•	Adding and Updating the Products.
•	How to give limited access to specific users like staff and customers.
•	How to navigate through the web application.
•	Navigation through the backend and all the essential functions.
•	How to place an order?
•	How to add an account to receive payments for the customer purchases.
•	Different payment modes integration like Debit and Credit Cards.
•	Periodic maintenance guidelines.

This engineer can be hired by the business entity or can be appointed by our organization (which is recommended) as he/she is vital for the website to function properly. Once the website is up and running. Physical staff can be downsized in the store based on customer traffic. This helps in saving the company money and resources. The website can be easily integrated into the business ecosystem without disruption to the existing business model. The website is easily scalable based on the user traffic which shall reduce the maintenance costs of the website.

The business can also choose one of the two popular options to integrate the website into their Business.
1.	One Time Purchase: The website once built shall be sold along with the copyrights to the business based on the business requirements and the business is responsible for the proper functioning and maintenance of the website.
Note: Customer Service shall be provided if needed on a periodic basis with a fixed fee.
 
 
2.	Subscription Service: The website shall be built and maintained by our organization and based on the business requirements, changes can be made to the website. This method helps the business to not worry about the functioning of the website. This Subscription service provides 24/7 customer service.


Any issues that occurred shall be notified to us. Our technical team shall provide on-site assistance in resolving the issue. 

## Traceability links
By using the traceability links, appropriate link between the artifacts (Use case diagram, Class diagram and Activity diagram) with the functional and non-functional requirement in order for better understanding of relation between Artifacts and Functional requirements with the help of Artifact ID, Artifact Name and Requirement ID.  



## Use Case Diagram Traceability 

| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
|[UseCase for Customer interface] (https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Usecase%20Diagrams%20-%20E%20commerce%20Website.pdf) | Browsing Order catalogue | FR1, FR2, FR3, FR4, FR7, FR16,NFR6, NFR7, NFR9, NFR10, NFR17,NFR19,NFR22 | 
|[UseCase for Customer interface] (https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Usecase%20Diagrams%20-%20E%20commerce%20Website.pdf) |Updating the Cart details and Checking out for Payment| FR6, FR7, FR9, FR10, FR19,FR20, FR21, FR22, FR24, FR25,NFR24,NFR22, NFR11  |
| [UseCase for Admin interface] (https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Usecase%20Diagrams%20-%20E%20commerce%20Website.pdf)  |Managing Inventories and Authenticating Customers and Orders  | FR11, FR12, FR13, FR15, NFR16, NFR25|



## Class Diagram Traceability 

| Artifact Name |  Requirement ID |

| [Signup and Upgraded cart details](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/CIS641%20Assignment%2005.pdf)| FR5, FR7, FR9, NFR2,NFR5 |
| [Admin authenticating Payments and Invoice](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/CIS641%20Assignment%2005.pdf) | FR25, FR23, FR, NFR,NFR |


## Activity Diagram Traceability 

| Artifact ID | Artifact Name | Requirement ID | 

|[Activity Diagram 1](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Activity%20Diagrams%20E%20commerce%20Website.pdf) | Activity Diagram for Customer  Interface | FR1-5, FR6, FR7, FR9, FR10, FR16, FR17, FR19, FR20, FR21, FR24, FR25, NFR2, NFR3, NFR6, NFR8, NFR10, NFR24 |
|[ActivityDiagram 2](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Activity%20Diagrams%20E%20commerce%20Website.pdf) | Activity Diagram for Admin Interface | FR11, FR12, FR13, FR14, FR15, NFR11, NFR12 NFR13, NFR16, NFR17, NFR18, NFR20, NFR22, NFR24,NFR25 |





# Software Artifacts

< An software artifact is a model which shows the structed flow of how exactly the work takes place. >

* [Class Diagram](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/CIS641%20Assignment%2005.pdf)
* [Activity Diagram](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Activity%20Diagrams%20E%20commerce%20Website.pdf)
* [Mapping Diagram](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/641%20inclass%20assignment%20(1).pdf)
* [Customer Usecase Description](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Customer%20Use%20case%20Description.pdf)
* [Window Navigation Diagram](https://github.com/gonehitesh/GVSU-CIS641-Alpha/blob/master/artifacts/functional-models/Windows%20Navigation%20Diagram%20for%20Customer.png)


