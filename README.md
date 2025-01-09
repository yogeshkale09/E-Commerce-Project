# E-Commerce-Django-Project

## Project Overview

This project is a comprehensive e-commerce platform built using Django. It provides functionality to list, search, and view product details while enabling a seamless cart and checkout experience. The project integrates modern web development practices with Django's powerful backend features, making it a practical guide for building scalable e-commerce applications.
![Screenshot 2025-01-09 140720](https://github.com/user-attachments/assets/8a6fd1e2-f0ef-470d-963c-2c43b6c0b453)

---
## Features and Steps Implemented

### 1. *Creating Product Model*

- Defined a⁣Product model in⁣models.py to represent the e-commerce products.
- The model includes fields such as title, description, price, image, and stock.

### 2. *Add Products to Database*

- Added product entries using Django's admin interface or scripts.
- Ensured proper data validation for all fields.

### 3. *Display Products on Index Page*

- Designed the index page using HTML and Bootstrap to showcase product cards.
- Integrated Django template tags to dynamically render products from the database.

### 4. *Adding CSS to Our Site*

- Added custom CSS and Bootstrap for styling the site.
- Ensured responsiveness for a better user experience across devices.

### 5. *Search Functionality*

- Implemented a search bar to filter products by title or description.
- Enhanced user navigation and product discovery.

### 6. *Adding Pagination*

- Integrated Django's Paginator to divide products across multiple pages.
- Improved page load times and user accessibility.

### 7. *Creating the Detail View for Products*

- Built a DetailView to display detailed information about a single product.
- Linked the detail view to the product's unique id.

### 8. *Using Local Storage to Save Cart Items*

- Utilized JavaScript's localStorage to persist cart items on the client side.
- Enabled cart retention even after page reloads.

### 9. *Adding Query & Creating the Cart*

- Set up a cart model to store user-selected items and quantities.
- Allowed adding and removing items dynamically.

### 10. *Getting Product's ID*

- Retrieved product IDs dynamically when a button is clicked.
- Enabled precise item identification for cart operations.

### 11. *Saving Items into Cart*

- Stored selected items in the localStorage or backend cart model.
- Updated the cart's state dynamically.

### 12. *Displaying Number of Items on Navbar*

- Added a cart icon with a dynamic badge showing the number of items.
- Updated the badge in real-time using JavaScript.

### 13. *Adding a Popover*

- Introduced Bootstrap popovers to display cart previews.
- Enhanced usability by showing a quick overview of cart items.

### 14. *Modifying Popover Content*

- Dynamically updated popover content based on cart state.
- Improved interactivity for users.

### 15. *Adding Cart Items in Popover*

- Listed items in the cart directly within the popover.
- Displayed item names, quantities, and prices.

### 16. *Checkout Page Template*

- Designed a checkout page to finalize orders.
- Included a summary of cart items, a total price, and a form for user details.

### 17. *Modifying Local Storage*

- Allowed users to update cart items directly from the cart or checkout page.
- Synchronized localStorage changes with the cart UI.

### 18. *Adding Cart Items to List Group*

- Displayed cart items in a Bootstrap list group on the checkout page.
- Highlighted product details for user clarity.

### 19. *Adding Checkout Form*

- Created a form for users to input shipping and payment details.
- Validated form data before order submission.

### 20. *Adding Cart Items to Database*

- Saved cart items and user details into the database upon checkout.
- Linked cart items with a unique order ID.

### 21. *Adding Item Prices*

- Included individual product prices in the cart.
- Dynamically updated the total price as items were added or removed.

### 22. *Calculating Order Total*

- Computed the total cost of items in the cart, including taxes or discounts.
- Displayed the final price prominently on the checkout page.

### 23. *Adding Order Total to Database*

- Saved the computed order total alongside cart items in the database.
- Ensured accurate order tracking for both users and administrators.

### 24. *Fixing the Add-to-Cart Bug*

- Debugged and resolved issues with item duplication or incorrect quantities.
- Ensured a smooth and error-free cart experience.


## How to Run the Project

1. Set up a virtual environment and install the dependencies:

   pip install -r requirements.txt
   
2. Apply migrations to set up the database:
   
   python manage.py migrate
   
3. Run the development server:
   
   python manage.py runserver
   
4. Open your browser and navigate to http://127.0.0.1:8000/.


## Tools and Technologies Used

- *Backend:* Django
- *Frontend:* HTML, CSS, Bootstrap, JavaScript, jQuery
- *Database:* SQLite

---

## Future Enhancements

- User authentication for personalized experiences.
- Integration with payment gateways.
- Advanced filtering and sorting for products.
- Responsive design improvements for mobile devices.

---
