# Alpha WEB

# Introduction

This Web Development project deals with developing an E-commerce Website. It provides the user with a list of the different products available for purchase in the online store.A shopping cart is provided. After the products added into the cart, user can proceed to payment. The system is implemented using Python’s web framework Django and SQLite Database which comes with the framework.

The website will display products, customers can view and select products, customer can remove products from their cart specifying the quantity of each item. Selected items will be stored in a cart. At checkout, the items in the cart will be presented as an order. Customers can pay for the items in the cart through a payment portal to complete the order. The project also provides security with the use of login ID and passwords, so that no unauthorized users can access your account. Only authorized person with access authority can access the software.

## Features Included

* Product Page
* Shopping Cart
* Responsive, user-friendly design
* Paypal payment integration
* User access control

# Technologies Used

* Python's Django framework V3.2.8
* SQLlite
* Microsoft VS
* HTML
* CSS
* Javascript

## How to run the Project.

Make sure that you are on the latest version of python on your system and have pip installed.

1. Clone the repositery with the following command.
```sh
git clone https://github.com/gonehitesh/GVSU-CIS641-Alpha.git
```
2. cd into the project directory.
```sh
cd GVSU-CIS641-Alpha/website/alphaweb/
```
3. Create a virtual environment.
```sh
python -m venv env
env\Scripts\activate
```
4. Install the requirements and run the server.
```sh
pip install -r requirements.txt
python manage.py runserver
```
5. Access the website at http://127.0.0.1:8000/
6. Access the admin page at http://127.0.0.1:8000/admin
7. For creating the superuser and to access the database.
```sh
python manage.py createsuperuser
python manage.py runserver
```
8. Don't forget to migrate the server after any changes.
```sh
python manage.py migrate
```
## Team Members

- Member 1 : [Hitesh Gone](https://github.com/gonehitesh/CIS641-HW2-Gone)
- Member 2 :[Vamshi Krishna Reddy](https://github.com/pvkr105/641-HW2-Purumandla)
- Member 3 :[Gurucharan parsa](https://github.com/charanparsa/CIS641-HW2-parsa)
- Member 4 : [Rithwik Sagar Kondala](https://github.com/rithwik05/641-HW2-kondala)

