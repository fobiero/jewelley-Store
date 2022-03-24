# Jewelry Store
This is a simple ecommerce web-portal that allows users to ciew prefered product and add to cart to purchase. 
## Features of this Project

### A. Admin Users Can
1. Manage Category (Add, Update, Filter and Delete)
2. Manage Products (Add, Update, Filter and Delete)
3. Manage Users (Update, Filter and Delete)
4. Manage Orders (View and Process)

### B. Non-Registered Users Can
1. View Products (Can filter based on category)
2. Explore Product Details and Related Products


### C. Registered Users Can Can
1. All ot Non-Registered Users
2. Add to Cart
3. Pay with PayPal or Debit/Credit Card and Order
4. See the Order Status
5. See Order History
6. Update Profile 
7. Change Password
8. Reset Password


## How to Install and Run this project?

### Pre-Requisites & technologies used:
* gitbash
* Python 
* HTML5
* Bootstrap
* Postgresql
* Django
* CSS3


### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

**3. Clone this project**
```
$  git clone https://github.com/fobiero/jewelley-Store
```

Then, Enter the project
```
$  cd jewellery-store
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**5. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```

**6. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

**7. Login Credentials**

Create Super User (Admin) with prefered password

Command for PC:
```
$  python manage.py createsuperuser
```

Command for MAC:
```
$  python3 manage.py createsuperuser
```

## Authors & Contributors 

* **Obiero felix** - *Initial work* - [github profile](https://github.com/fobiero)

## License

This project is licensed under the [MIT](LICENCE) license.



