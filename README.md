# Tretto.eg - Online Retail Management System

Tretto is a full-stack, web-based e-commerce platform specialized in retail management (Clogs, Slippers & Bags)[span_2](start_span)[span_2](end_span). This project is engineered with a strong emphasis on clean code, utilizing **Object-Oriented Programming (OOP)**, the **MVC architectural pattern**, and standard **Design Patterns** to ensure scalability, security, and maintainability[span_3](start_span)[span_3](end_span).

## 🏗️ Architecture & OOP Concepts
The core strength of this system lies in its technical foundation:
* **MVC Architecture:** Strict separation of concerns[span_4](start_span)[span_4](end_span).
  * **Controllers:** Handle HTTP request routing and coordinate business logic[span_5](start_span)[span_5](end_span).
  * **Models:** Encapsulate database queries, operations, and business rules[span_6](start_span)[span_6](end_span).
  * **Views:** Render the HTML frontend output using PHP templates[span_7](start_span)[span_7](end_span).
* **Design Patterns Implemented:**
  * **Factory Pattern:** Utilized `ProductFactory` for structured and dynamic object creation[span_8](start_span)[span_8](end_span).
  * **Validator Pattern:** Dedicated validation classes (`LoginValidator`, `RegistrationValidator`, `CheckoutValidator`) to securely handle user input and server-side validation[span_9](start_span)[span_9](end_span).
* **Security:** Role-based access control (RBAC) protecting admin routes, session protection, and secure hashed passwords[span_10](start_span)[span_10](end_span).

## 🌟 Key Features

**Customer Shopping Experience:**
* **Advanced Browsing:** Search, sort (price low/high), and multi-criteria filtering (by collection, size, color, and price range) without page reloads via JS[span_11](start_span)[span_11](end_span).
* **Product Details:** Support for product variants (sizes/colors), stock tracking, and multiple image galleries[span_12](start_span)[span_12](end_span).
* **Order Flow:** Dynamic cart management, Wishlist/Favorites system, and secure checkout[span_13](start_span)[span_13](end_span).
* **Payments:** Supports both Cash on Delivery (COD) and Visa payment flows[span_14](start_span)[span_14](end_span).
* **Post-Purchase:** Real-time order tracking, submission of product reviews, and an automated system for requesting Refunds or Exchanges[span_15](start_span)[span_15](end_span).

**Admin Dashboard & Management:**
* **Catalog Management:** Full CRUD operations for products, variants, images, and collections[span_16](start_span)[span_16](end_span).
* **Order Processing:** Update order statuses (Pending, Shipped, Delivered) reflecting instantly on the customer's end[span_17](start_span)[span_17](end_span).
* **Request Moderation:** Dedicated panels to approve/deny customer Refund and Exchange requests[span_18](start_span)[span_18](end_span).
* **Store Management:** Moderate customer reviews and update physical store locations and support contact info[span_19](start_span)[span_19](end_span).

## 💻 Tech Stack
* **Backend:** PHP (OOP, MVC)[span_20](start_span)[span_20](end_span)
* **Database:** MySQL / phpMyAdmin[span_21](start_span)[span_21](end_span)
* **Frontend:** HTML, CSS, JavaScript[span_22](start_span)[span_22](end_span)
* **Server:** Apache / XAMPP[span_23](start_span)[span_23](end_span)

## 🗄️ Database Schema
A highly normalized relational database containing 19 tables, including[span_24](start_span)[span_24](end_span):
`users`, `customers`, `admins`, `products`, `product_variants`, `collections`, `orders`, `order_items`, `payments`, `refunds`, `exchanges`, `reviews`, and `cart_items`[span_25](start_span)[span_25](end_span).

## 🧪 Quality Assurance & Testing
The system underwent rigorous manual testing and technical validation:
* **Test Coverage:** 47 comprehensive test cases executed covering all modules (Registration, Checkout, DB CRUD, Admin restrictions), with a 100% pass rate[span_26](start_span)[span_26](end_span).
* **Code Quality:** All PHP controller, model, and view files passed strict PHP syntax validation (`php -l`)[span_27](start_span)[span_27](end_span).
