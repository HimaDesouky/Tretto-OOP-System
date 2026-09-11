# Tretto.eg - Online Retail Management System

Tretto is a full-stack, web-based e-commerce platform specialized in retail management (Clogs, Slippers & Bags). This project is engineered with a strong emphasis on clean code, utilizing **Object-Oriented Programming (OOP)**, the **MVC architectural pattern**, and standard **Design Patterns** to ensure scalability, security, and maintainability.

## 🏗️ Architecture & OOP Concepts
The core strength of this system lies in its technical foundation:
* **MVC Architecture:** Strict separation of concerns.
  * **Controllers:** Handle HTTP request routing and coordinate business logic.
  * **Models:** Encapsulate database queries, operations, and business rules.
  * **Views:** Render the HTML frontend output using PHP templates.
* **Design Patterns Implemented:**
  * **Factory Pattern:** Utilized `ProductFactory` for structured and dynamic object creation.
  * **Validator Pattern:** Dedicated validation classes (`LoginValidator`, `RegistrationValidator`, `CheckoutValidator`) to securely handle user input and server-side validation.
* **Security:** Role-based access control (RBAC) protecting admin routes, session protection, and secure hashed passwords.

## 🌟 Key Features

**Customer Shopping Experience:**
* **Advanced Browsing:** Search, sort (price low/high), and multi-criteria filtering (by collection, size, color, and price range) without page reloads via JS.
* **Product Details:** Support for product variants (sizes/colors), stock tracking, and multiple image galleries.
* **Order Flow:** Dynamic cart management, Wishlist/Favorites system, and secure checkout.
* **Payments:** Supports both Cash on Delivery (COD) and Visa payment flows.
* **Post-Purchase:** Real-time order tracking, submission of product reviews, and an automated system for requesting Refunds or Exchanges.

**Admin Dashboard & Management:**
* **Catalog Management:** Full CRUD operations for products, variants, images, and collections.
* **Order Processing:** Update order statuses (Pending, Shipped, Delivered) reflecting instantly on the customer's end.
* **Request Moderation:** Dedicated panels to approve/deny customer Refund and Exchange requests.
* **Store Management:** Moderate customer reviews and update physical store locations and support contact info.

## 💻 Tech Stack
* **Backend:** PHP (OOP, MVC)
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript
* **Server:** Apache / XAMPP

## 🗄️ Database Schema
A highly normalized relational database containing 19 tables, including:
`users`, `customers`, `admins`, `products`, `product_variants`, `collections`, `orders`, `order_items`, `payments`, `refunds`, `exchanges`, `reviews`, and `cart_items`.

## 🧪 Quality Assurance & Testing
The system underwent rigorous manual testing and technical validation:
* **Test Coverage:** 47 comprehensive test cases executed covering all modules (Registration, Checkout, DB CRUD, Admin restrictions), with a 100% pass rate.
* **Code Quality:** All PHP controller, model, and view files passed strict PHP syntax validation (`php -l`).
