# Selenium-Example
The following test cases were created from the website https://www.saucedemo.com/.

**Test Case 1: User Login – Valid Credentials**

**Test Case Objective**

Verify that a registered user can successfully log in with valid credentials.

**Preconditions**

User account exists

Application is accessible

**Test Steps** (Manual Logic)

1- Navigate to Login page

2- Enter valid username

3- Enter valid password

4- Click Login

5- Verify dashboard loads successfully

**Expected Result**

User is authenticated and redirected to the dashboard.

___________________________________________________________________________________

**Test Case 2: Add Item to Cart & Verify Count**

**Test Case Objective**

Verify that a user can add an item to the cart and cart count updates correctly.

**Preconditions**

User is logged in

Product catalog is available

**Test Steps**

1- Navigate to products page

2- Click “Add to Cart” on a product

3- Verify cart badge increments

**Expected Result**

Cart count increases to reflect added item.
