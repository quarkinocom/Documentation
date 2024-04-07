---
sidebar_position: 5
---

# Shopping Cart
The Cart module enriches Quarkino by integrating the essential processes and workflows of pre-ordering and order placement, centered around the product core. It facilitates the activation of shopping cart capabilities for various content types, leveraging the e-commerce template for a holistic shopping experience. Through the meticulous settings in the Sales Rules section, it offers comprehensive management over product presentation and sales, thereby culminating the sales cycle with precision and user-centric approaches.

## List of Features

- **Pre-Ordering and Order Management:** Enables the activation of pre-order and order functionalities, allowing for detailed management of the user's purchase journey.
- **Order Status Customization:** Offers the flexibility to alter the status of orders either automatically or manually, adapting to specific business needs.
- **Integrated User Order and Invoice Management:** Streamlines the management of user orders and invoices, facilitating smooth operational flows.
- **Comprehensive Payment Management:** Incorporates wallet utilization, comprehensive payment management, and the application of discount coupons, enhancing the checkout process.
- **Return and Complaints System:** Implements a system for users to register complaints and returns electronically, ensuring customer satisfaction and feedback loops.
- **Inventory Management for Physical Products:** Delivers robust inventory management capabilities, essential for physical product sales and stock management.
- **Special Sales and Discounts:** Enables the creation of long-term discounts and special sales, allowing for dynamic pricing strategies and promotional campaigns.

## Usability Keys

- **Streamlined Order Processing:** Ensures a smooth and efficient process for managing pre-orders and orders, enhancing the user experience.
- **Flexible Sales Regulations:** Adapts to diverse sales strategies and business models through customizable sales regulations and settings.
- **Enhanced Customer Satisfaction:** Facilitates a robust system for handling complaints and returns, directly contributing to improved customer service.
- **Comprehensive Inventory Oversight:** Provides detailed insights into stock levels, sales trends, and inventory management, essential for effective product management.
- **Dynamic Pricing and Promotions:** Allows for the easy implementation of discounts and special sales, catering to various marketing strategies and customer incentives.

These endpoints and features underscore the Cart feature vital role in Quarkino's ecosystem, offering a foundation upon which a versatile and dynamic e-commerce platform can thrive, catering to a wide range of business requirements and customer preferences.

## **Guest Endpoints**

Access to them without any token.

### **Sale setting**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-sale-setting](https://yourprojects.quarkino.io/api/modular/v1/cart-order-sale-setting)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is utilized to retrieve settings and configurations related to sales and orders within a cart system. By issuing a GET request, it allows users, particularly administrators or managers, to access settings that dictate the behavior of sales transactions, such as tax rates, shipping fees, discount policies, and payment options. This information is crucial for ensuring that the cart system operates in accordance with the business's financial and operational policies, providing a seamless and accurate checkout experience for customers. It supports the management of dynamic sales conditions, such as promotional discounts or special shipping rates, enabling efficient adjustments to the sales process that reflect current promotions or policy changes.

[Postman Link](https://google.com/)

### **Order Find**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-track](https://yourprojects.quarkino.io/api/modular/v1/cart-order-track)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint enables users to track the status of their orders. Accessible via a GET request, it requires the order ID as a parameter to fetch the current status and potentially detailed tracking information for the order. This functionality is essential for providing transparency and reassurance to customers regarding the progress of their purchases. It enhances the user experience by offering real-time updates on order processing, shipping, and delivery stages. The endpoint caters to a fundamental need in e-commerce platforms, allowing users to stay informed about their order's journey from placement to delivery, contributing to customer satisfaction and trust in the service.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **Claim User Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-user-save](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-user-save)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed as a POST method for submitting a claim related to an order. It requires bearer token authentication, ensuring that only authenticated users can make a claim submission. The request body must include an id (in string format) and items (as an array), which specify the order and the items within that order for which the claim is being made. This functionality is essential for users who need to submit claims related to their orders, allowing for a structured and secure way to manage such requests within the system.

[Postman Link](https://google.com/)

### **My Order Add Item**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-add-item](https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-add-item)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed to allow users to add item to their current order and update the order details accordingly. It is a POST request that updates the user's order by adding new item, refreshing the order to remove any out-of-stock item, and updating the prices as necessary. This ensures that the order reflects the most current availability and pricing information, providing a seamless and accurate shopping experience for the user.

[Postman Link](https://google.com/)

### **My Order Add Items**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-add-items](https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-add-items)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed to allow users to add items to their current order and update the order details accordingly. It is a POST request that updates the user's order by adding new items, refreshing the order to remove any out-of-stock items, and updating the prices as necessary. This ensures that the order reflects the most current availability and pricing information, providing a seamless and accurate shopping experience for the user.

[Postman Link](https://google.com/)

### **My Order Coupon Inquiry**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-coupon-inquiry](https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-coupon-inquiry)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET method designed to evaluate the given discount coupons and provide the results without affecting the prices. This functionality is key for users wanting to verify the applicability and value of discount coupons for their orders in a straightforward manner, ensuring transparency and efficiency in the purchasing process by allowing them to assess potential savings before finalizing their orders.

[Postman Link](https://google.com/)

### **My Order Evacuate**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-evacuate](https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-evacuate)

**Permission:** User

**Method:** DELETE

**Description:** The endpoint is a DELETE method designed to clear an online user's order by removing all items inside it as well as the main order record itself. This function is crucial for scenarios where a user decides to start over with their shopping cart or needs to remove their current selection due to a change in decision. It provides a straightforward means to reset the order status to a clean state, ensuring that users can manage their orders flexibly and efficiently.

[Postman Link](https://google.com/)

### **My Order Refresh**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-refresh](https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-refresh)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET method intended to update the current state of a user's order. It focuses on refreshing the order by removing items that are out-of-stock and updating the prices to reflect the most current values. This endpoint ensures that users have an accurate view of their order, with up-to-date availability and pricing information, before they proceed to checkout. This functionality is essential for maintaining transparency and trust with users by ensuring that their cart reflects real-time data regarding product availability and pricing.

[Postman Link](https://google.com/)

### **My Order Remove Item**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-remove-item](https://yourprojects.quarkino.io/api/modular/v1/cart-my-order-remove-item)

**Permission:** User

**Method:** DELETE

**Description:** The endpoint is a DELETE method that facilitates the removal of a specific item from the user's current order. It requires input parameters such as id (in string format), and optionally, including (as an array), get_old (boolean), count_removed (boolean), and count_updated (boolean) to manage the item removal process effectively. This endpoint enhances user experience by allowing them to modify their order by removing unwanted items before finalizing their purchase, ensuring that the cart reflects only the items they wish to proceed with.

[Postman Link](https://google.com/)

### **My Orders List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-my-orders-list](https://yourprojects.quarkino.io/api/modular/v1/cart-my-orders-list)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET method designed to retrieve the list of orders for an online user. It requires authentication via a bearer token to ensure that the request is made by an authenticated user. The endpoint aims to provide users with a comprehensive view of their order history, enabling them to track and manage their orders efficiently. This functionality is crucial for enhancing the user experience by providing easy access to order details, statuses, and other relevant information.

[Postman Link](https://google.com/)

### **Order Finalize**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-finalize](https://yourprojects.quarkino.io/api/modular/v1/cart-order-finalize)

**Permission:** User

**Method:** POST

**Description:** The endpoint is a POST method intended to finalize a user's order process. This endpoint requires several pieces of information to be sent in the request body, including id, shipping_method, shipping_slot, address, payable_amount, coupons, and order_description. It is designed to process the final steps of an order, ensuring all necessary details for shipping, payment, and order specifics are correctly submitted and recorded. This action marks the transition of an order from being in progress to completed, enabling the fulfillment process to begin.

[Postman Link](https://google.com/)

### **Payment Offline Transaction Make**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-payment-offline-transaction-make](https://yourprojects.quarkino.io/api/modular/v1/cart-payment-offline-transaction-make)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed for making an offline payment transaction. It is a POST method that requires a body with specific parameters such as id, amount (as a float), tracking_number, effected_at (date/time when the transaction was made), path_id, and receipt (a string that can be used as proof of the offline transaction). This endpoint facilitates the integration of offline payment methods into the system, allowing users to register payments made outside the online platform. It ensures that all transactions, regardless of how they are processed, are accounted for within the system, thereby maintaining accurate financial records.

[Postman Link](https://google.com/)

### **Payment Paths List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-payment-paths-list](https://yourprojects.quarkino.io/api/modular/v1/cart-payment-paths-list)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET method used to retrieve the list of available online and offline payment gateways. This functionality is vital for users to understand their payment options during the checkout process, enabling them to choose the most suitable payment method. By providing a comprehensive list of payment paths, this endpoint ensures that users have all necessary information to make informed decisions regarding their payment strategy.

[Postman Link](https://google.com/)

### **Payment Transaction Make**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-payment-transaction-make](https://yourprojects.quarkino.io/api/modular/v1/cart-payment-transaction-make)

**Permission:** User

**Method:** POST

**Description:** The endpoint is a POST method designed to create a payment transaction record and return a payment URL. This endpoint plays a crucial role in the payment process, enabling users to initiate a payment transaction and providing them with a URL to complete the payment. It facilitates the seamless integration of payment processing into the user's checkout flow, ensuring a smooth and secure transaction experience.

[Postman Link](https://google.com/)

### **Shipping Suitable Methods**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-shipping-suitable-methods](https://yourprojects.quarkino.io/api/modular/v1/cart-shipping-suitable-methods)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET method designed to retrieve a list of suitable shipping methods available for the user's current order. It enables users to view and select from various shipping options that match their order's requirements and preferences. By providing a dynamic and tailored list of shipping methods, this endpoint plays a crucial role in optimizing the checkout process, ensuring users have access to the most relevant and cost-effective shipping options.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.

### **Claim Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the claim in edit mode

[Postman Link](https://google.com/)

### **Claim Finalization**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-finalization](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-finalization)

**Permission:** Admin

**Method:** POST

**Description:** finalization the claim

[Postman Link](https://google.com/)

### **Claim Item Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-item-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-item-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the item of claim

[Postman Link](https://google.com/)

### **Claim Item Processing**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-item-processing](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-item-processing)

**Permission:** Admin

**Method:** POST

**Description:** processing of per item of claims

[Postman Link](https://google.com/)

### **Claim Order Get**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-order-get](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-order-get)

**Permission:** Admin

**Method:** GET

**Description:** get a cart order

[Postman Link](https://google.com/)

### **Claim Orders Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-orders-search](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-orders-search)

**Permission:** Admin

**Method:** GET

**Description:** get list of orders based on search

[Postman Link](https://google.com/)

### **Claim Payment Processing Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-payment-processing-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-payment-processing-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the payment processing data for claims

[Postman Link](https://google.com/)

### **Claim Payment Processing Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-payment-processing-save](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-payment-processing-save)

**Permission:** Admin

**Method:** POST

**Description:** Save the payment processing transaction for claims

[Postman Link](https://google.com/)

### **Claim Payment Status Change**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-payment-status-change](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-payment-status-change)

**Permission:** Admin

**Method:** POST

**Description:** Change Transactions status of claim

[Postman Link](https://google.com/)

### **Claim Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-save](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-save)

**Permission:** Admin

**Method:** POST

**Description:** save a claim for a order

[Postman Link](https://google.com/)

### **Claim Status Change**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claim-status-change](https://yourprojects.quarkino.io/api/modular/v1/cart-claim-status-change)

**Permission:** Admin

**Method:** POST

**Description:** change status of claim

[Postman Link](https://google.com/)

### **Claim Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-claims-grid](https://yourprojects.quarkino.io/api/modular/v1/cart-claims-grid)

**Permission:** Admin

**Method:** GET

**Description:** Claim Grid

[Postman Link](https://google.com/)

### **Coupon Processing Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-coupon-processing-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-coupon-processing-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the coupon processing modal

[Postman Link](https://google.com/)

### **Coupon Processing Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-coupon-processing-save](https://yourprojects.quarkino.io/api/modular/v1/cart-coupon-processing-save)

**Permission:** Admin

**Method:** POST

**Description:** Save a coupon code

[Postman Link](https://google.com/)

### **Inventory Processing Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-inventory-processing-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-inventory-processing-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the inventory processing form data

[Postman Link](https://google.com/)

### **Inventory Processing Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-inventory-processing-save](https://yourprojects.quarkino.io/api/modular/v1/cart-inventory-processing-save)

**Permission:** Admin

**Method:** POST

**Description:** Save the Inventory processing of an order

[Postman Link](https://google.com/)

### **Invoice Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-invoice-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-invoice-fetch)

**Permission:** Admin

**Method:** GET

**Description:** get the invoice

[Postman Link](https://google.com/)

### **Invoice Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-invoice-save](https://yourprojects.quarkino.io/api/modular/v1/cart-invoice-save)

**Permission:** Admin

**Method:** POST

**Description:** generate and regenerate invoice

[Postman Link](https://google.com/)

### **Invoices Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-invoices-grid](https://yourprojects.quarkino.io/api/modular/v1/cart-invoices-grid)

**Permission:** Admin

**Method:** GET

**Description:** get invoices grid

[Postman Link](https://google.com/)

### **Method Category Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-method-category-search](https://yourprojects.quarkino.io/api/modular/v1/cart-method-category-search)

**Permission:** Admin

**Method:** GET

**Description:** search the label for shipping rule

[Postman Link](https://google.com/)

### **Order Close**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-close](https://yourprojects.quarkino.io/api/modular/v1/cart-order-close)

**Permission:** Admin

**Method:** POST

**Description:** Close an order

[Postman Link](https://google.com/)

### **Order Comment**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-comment](https://yourprojects.quarkino.io/api/modular/v1/cart-order-comment)

**Permission:** Admin

**Method:** POST

**Description:** add a comment to the order timeline, by admin or the self customer.

[Postman Link](https://google.com/)

### **Order Coupon Mark As Unused**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-coupon-mark-as-unused](https://yourprojects.quarkino.io/api/modular/v1/cart-order-coupon-mark-as-unused)

**Permission:** Admin

**Method:** POST

**Description:** Detach a coupon code from an order

[Postman Link](https://google.com/)

### **Order Fetch New**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-create-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-order-create-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the required data to display the order and pre-order editor for a new record.

[Postman Link](https://google.com/)

### **Order Details**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-details](https://yourprojects.quarkino.io/api/modular/v1/cart-order-details)

**Permission:** Admin

**Method:** GET

**Description:** get the order details to the admin, or the self-customer.

[Postman Link](https://google.com/)

### **Order Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-order-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the required data to display the order and pre-order editor for an existing record. This is

[Postman Link](https://google.com/)

### **Order Reopen**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-reopen](https://yourprojects.quarkino.io/api/modular/v1/cart-order-reopen)

**Permission:** Admin

**Method:** POST

**Description:** Reopen an order

[Postman Link](https://google.com/)

### **Order Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-save](https://yourprojects.quarkino.io/api/modular/v1/cart-order-save)

**Permission:** Admin

**Method:** POST

**Description:** Save an order in the admin panel.

[Postman Link](https://google.com/)

### **Order Status Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-status-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-order-status-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the form, required for the admin to change the order status.

[Postman Link](https://google.com/)

### **Order Status Set**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-status-set](https://yourprojects.quarkino.io/api/modular/v1/cart-order-status-set)

**Permission:** Admin

**Method:** PUT

**Description:** set order status by admin

[Postman Link](https://google.com/)

### **Order Timeline**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-order-timeline](https://yourprojects.quarkino.io/api/modular/v1/cart-order-timeline)

**Permission:** Admin

**Method:** GET

**Description:** get the order timeline, with enough data to render filters and action buttons.

[Postman Link](https://google.com/)

### **Orders Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-orders-grid](https://yourprojects.quarkino.io/api/modular/v1/cart-orders-grid)

**Permission:** Admin

**Method:** GET

**Description:** get orders grid

[Postman Link](https://google.com/)

### **Panel Menu**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-panel-menu](https://yourprojects.quarkino.io/api/modular/v1/cart-panel-menu)

**Permission:** Admin

**Method:** GET

**Description:** get the cart process mega-menu used in the admin panel.

[Postman Link](https://google.com/)

### **Payment Processing Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-payment-processing-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-payment-processing-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the payment processing form data

[Postman Link](https://google.com/)

### **Payment Processing Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-payment-processing-save](https://yourprojects.quarkino.io/api/modular/v1/cart-payment-processing-save)

**Permission:** Admin

**Method:** POST

**Description:** Save the payment transactions

[Postman Link](https://google.com/)

### **Payment Status Change**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-payment-status-change](https://yourprojects.quarkino.io/api/modular/v1/cart-payment-status-change)

**Permission:** Admin

**Method:** POST

**Description:** Change Transactions status

[Postman Link](https://google.com/)

### **Pre-Order convert to Order**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-pre-order-convert](https://yourprojects.quarkino.io/api/modular/v1/cart-pre-order-convert)

**Permission:** Admin

**Method:** PUT

**Description:** convert an approved pre-order to an approved order.

[Postman Link](https://google.com/)

### **PreOrders Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-pre-orders-grid](https://yourprojects.quarkino.io/api/modular/v1/cart-pre-orders-grid)

**Permission:** Admin

**Method:** GET

**Description:** get pre_orders grid

[Postman Link](https://google.com/)

### **Rulebook Category Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-rulebook-category-search](https://yourprojects.quarkino.io/api/modular/v1/cart-rulebook-category-search)

**Permission:** Admin

**Method:** GET

**Description:** search the label for coupons rule

[Postman Link](https://google.com/)

### **Rulebook Product Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-rulebook-product-search](https://yourprojects.quarkino.io/api/modular/v1/cart-rulebook-product-search)

**Permission:** Admin

**Method:** GET

**Description:** search the posts for coupons rule

[Postman Link](https://google.com/)

### **Sale Setting Seller Info Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-sale-setting-seller-info-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-sale-setting-seller-info-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the seller info

[Postman Link](https://google.com/)

### **Sale Setting Seller Info Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-sale-setting-seller-info-save](https://yourprojects.quarkino.io/api/modular/v1/cart-sale-setting-seller-info-save)

**Permission:** Admin

**Method:** POST

**Description:** save the seller info in sale setting

[Postman Link](https://google.com/)

### **Shipping Processing Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-shipping-processing-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-shipping-processing-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the shipping processing system

[Postman Link](https://google.com/)

### **Shipping Processing Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-shipping-processing-save](https://yourprojects.quarkino.io/api/modular/v1/cart-shipping-processing-save)

**Permission:** Admin

**Method:** POST

**Description:** Save the shipping method

[Postman Link](https://google.com/)

### **User Address List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-user-address-list](https://yourprojects.quarkino.io/api/modular/v1/cart-user-address-list)

**Permission:** Admin

**Method:** GET

**Description:** the list of user

[Postman Link](https://google.com/)

### **User Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-user-search](https://yourprojects.quarkino.io/api/modular/v1/cart-user-search)

**Permission:** Admin

**Method:** GET

**Description:** search the user in order editor. It's not meant to support pagination, nor custom resource.

[Postman Link](https://google.com/)

### **Ware Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-ware-fetch](https://yourprojects.quarkino.io/api/modular/v1/cart-ware-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch a ware for order editor

[Postman Link](https://google.com/)

### **Ware Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/cart-ware-search](https://yourprojects.quarkino.io/api/modular/v1/cart-ware-search)

**Permission:** Admin

**Method:** GET

**Description:** search for a particular ware and get the relative prices. This is more than a simple combo.

[Postman Link](https://google.com/)
