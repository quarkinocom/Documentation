---
sidebar_position: 4
---

# Market
The Market module is a cornerstone for facilitating online business activities within Quarkino, offering extensive tools for product management, inventory control, and the execution of sales strategies. It is uniquely designed to support both physical and digital products, enabling administrators to oversee product portfolios, track inventory with precision, and customize the sales process according to business needs. Through its integration with the Content module, the Market module extends the functionality to include sales regulations, thereby enhancing product management and promotional activities.

## List of Features

- **Product Definition and Management**: Enables the categorization and detailed management of a wide range of products, accommodating various product attributes and types.
- **Inventory Management**: Offers comprehensive tools for tracking stock levels, including features for monitoring purchase prices, stock availability, reservations, and analyzing sales trends.
- **Sales Regulations**: Allows administrators to establish rules and settings that govern the sales process, including payment conditions, return policies, and sales channels.
- **Payment Gateway Integration**: Facilitates seamless transactions by supporting a variety of payment methods and gateways, ensuring a smooth checkout process for customers.
- **Tax Regulations and Compliance**: Provides tools for configuring tax settings applicable to different regions, aiding in compliance with local tax laws.
- **Discount Coupons and Special Sales**: Implements promotional strategies through the use of discount codes, special sales events, and long-term discount campaigns, driving sales and enhancing customer engagement.
- **Versatile Inventory Options**: Supports complex inventory scenarios, such as variant tracking for products with multiple options (e.g., colors, sizes) and bundle products that combine several items into a single offering.

## Usability Keys

- **Enhanced Sales Operations**: Streamlines the process of selling products online, from listing to transaction completion, ensuring a comprehensive and efficient sales cycle.
- **Detailed Inventory Insights**: Empowers businesses with detailed inventory tracking and analysis, enabling informed decision-making and optimal stock management.
- **Flexible Sales Configurations**: Offers the ability to customize sales strategies and processes, adapting to various business models and market demands.
- **Comprehensive Payment Solutions**: Simplifies the payment process for customers and businesses, supporting a wide range of payment methods for enhanced transaction flexibility.
- **Promotional Tools**: Facilitates the creation and management of promotional campaigns, leveraging discounts and special sales to attract customers and boost sales volumes.

## **Guest Endpoints**

Access to them without any token.

### **Product Wares Prices**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-product-wares-prices](https://yourprojects.quarkino.io/api/modular/v1/market-product-wares-prices)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint offers detailed pricing information for products within the marketplace. Through a GET request, it enables users to access prices for various wares or product variations, including standard pricing, discounted rates, bulk purchase deals, and any other price-related details. This functionality is essential for customers looking to make informed purchasing decisions, allowing them to compare prices across different products or sellers within the market. It supports transparency in pricing and helps in identifying the best deals or understanding pricing structures for specific products. Additionally, this endpoint can aid sellers in competitive pricing strategies by providing insights into market price trends and customer preferences.

[Postman Link](https://google.com/)

### **Products Filters**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-products-filters](https://yourprojects.quarkino.io/api/modular/v1/market-products-filters)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint provides a dynamic list of filters applicable to the marketplace's product listings. By making a GET request, users can retrieve the available filters, such as categories, brands, price ranges, ratings, and other attributes that can be used to refine product searches. This functionality is essential for enhancing the user experience in navigating through a vast array of products, allowing users to easily find products that meet their specific criteria. It supports a more tailored and efficient shopping experience by enabling users to sort and view products based on their preferences and needs, thereby improving product discoverability and satisfaction.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **Availability Alert**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-availability-alert](https://yourprojects.quarkino.io/api/modular/v1/market-availability-alert)

**Permission:** User

**Method:** POST

**Description:** The endpoint is a POST method aimed at enabling users to subscribe to alerts for the availability of specific products or items. When an item that a user is interested in becomes available, this system sends an alert to the user, informing them of the item's availability. This feature is particularly useful in scenarios where products frequently sell out or are in high demand, allowing users to be promptly informed when the item is back in stock and available for purchase. This enhances the shopping experience by ensuring users do not miss out on purchasing desired items due to them being out of stock.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.

### **Campaign Categories**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-campaign-categories](https://yourprojects.quarkino.io/api/modular/v1/market-campaign-categories)

**Permission:** Admin

**Method:** GET

**Description:** search the categories

[Postman Link](https://google.com/)

### **Campaign Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-campaign-fetch](https://yourprojects.quarkino.io/api/modular/v1/market-campaign-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the campaign

[Postman Link](https://google.com/)

### **Campaign Products**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-campaign-products](https://yourprojects.quarkino.io/api/modular/v1/market-campaign-products)

**Permission:** Admin

**Method:** GET

**Description:** the search in all products in this shop type or list of product a category

[Postman Link](https://google.com/)

### **Campaign Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-campaign-save](https://yourprojects.quarkino.io/api/modular/v1/market-campaign-save)

**Permission:** Admin

**Method:** POST

**Description:** save he campaign

[Postman Link](https://google.com/)

### **Category Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-category-search](https://yourprojects.quarkino.io/api/modular/v1/market-category-search)

**Permission:** Admin

**Method:** GET

**Description:** search the label for market types

[Postman Link](https://google.com/)

### **Dependable Wares**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-dependable-wares](https://yourprojects.quarkino.io/api/modular/v1/market-dependable-wares)

**Permission:** Admin

**Method:** GET

**Description:** Get dependable wares

[Postman Link](https://google.com/)

### **InventoryChanges Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-inventory-changes-grid](https://yourprojects.quarkino.io/api/modular/v1/market-inventory-changes-grid)

**Permission:** Admin

**Method:** GET

**Description:** get inventory_changes grid

[Postman Link](https://google.com/)

### **Inventory Fetch Form Configs**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-inventory-fetch-form-configs](https://yourprojects.quarkino.io/api/modular/v1/market-inventory-fetch-form-configs)

**Permission:** Admin

**Method:** GET

**Description:** Fetch needed configs of inventory form

[Postman Link](https://google.com/)

### **Inventory Form Ware Find**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-inventory-form-ware-find](https://yourprojects.quarkino.io/api/modular/v1/market-inventory-form-ware-find)

**Permission:** Admin

**Method:** GET

**Description:** find a ware for inventory form

[Postman Link](https://google.com/)

### **Inventory Report**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-inventory-report](https://yourprojects.quarkino.io/api/modular/v1/market-inventory-report)

**Permission:** Admin

**Method:** POST

**Description:** reports inventory

[Postman Link](https://google.com/)

### **Inventory Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-inventory-save](https://yourprojects.quarkino.io/api/modular/v1/market-inventory-save)

**Permission:** Admin

**Method:** POST

**Description:** Save new inventory change

[Postman Link](https://google.com/)

### **Inventory Uniques Combo**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-inventory-uniques-combo](https://yourprojects.quarkino.io/api/modular/v1/market-inventory-uniques-combo)

**Permission:** Admin

**Method:** GET

**Description:** get the combo of unique independent wares

[Postman Link](https://google.com/)

### **Post Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-post-fetch](https://yourprojects.quarkino.io/api/modular/v1/market-post-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the posts of market-template

[Postman Link](https://google.com/)

### **Post Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-post-save](https://yourprojects.quarkino.io/api/modular/v1/market-post-save)

**Permission:** Admin

**Method:** POST

**Description:** Save a post with market template in the admin panel

[Postman Link](https://google.com/)

### **Posts Mass Make Available**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-posts-mass-make-available](https://yourprojects.quarkino.io/api/modular/v1/market-posts-mass-make-available)

**Permission:** Admin

**Method:** PUT

**Description:** Make a number of products available

[Postman Link](https://google.com/)

### **Posts Mass Make Unavailable**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-posts-mass-make-unavailable](https://yourprojects.quarkino.io/api/modular/v1/market-posts-mass-make-unavailable)

**Permission:** Admin

**Method:** PUT

**Description:** Make a number of products unavailable

[Postman Link](https://google.com/)

### **Market Product Availability**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-product-availability](https://yourprojects.quarkino.io/api/modular/v1/market-product-availability)

**Permission:** Admin

**Method:** POST

**Description:** Get Product availability

[Postman Link](https://google.com/)

### **Product Wares**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-product-wares](https://yourprojects.quarkino.io/api/modular/v1/market-product-wares)

**Permission:** Admin

**Method:** GET

**Description:** Gets wares attached to a particular content post.

[Postman Link](https://google.com/)

### **Products List Preferences Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-products-list-preferences-form](https://yourprojects.quarkino.io/api/modular/v1/market-products-list-preferences-form)

**Permission:** Admin

**Method:** GET

**Description:** No description available

[Postman Link](https://google.com/)

### **Products List Preferences Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-products-list-preferences-save](https://yourprojects.quarkino.io/api/modular/v1/market-products-list-preferences-save)

**Permission:** Admin

**Method:** POST

**Description:** No description available

[Postman Link](https://google.com/)

### **Sale Settings Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-sale-settings-fetch](https://yourprojects.quarkino.io/api/modular/v1/market-sale-settings-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the sale-settings panel.

[Postman Link](https://google.com/)

### **Sale Settings Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-sale-settings-save](https://yourprojects.quarkino.io/api/modular/v1/market-sale-settings-save)

**Permission:** Admin

**Method:** PUT

**Description:** Save the sale settings.

[Postman Link](https://google.com/)

### **Tagging Search Data Trader Editor**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-tagging-search-data-trader-editor](https://yourprojects.quarkino.io/api/modular/v1/market-tagging-search-data-trader-editor)

**Permission:** Admin

**Method:** GET

**Description:** get market tagging on searching in data trader editor

[Postman Link](https://google.com/)

### **Unit Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-unit-save](https://yourprojects.quarkino.io/api/modular/v1/market-unit-save)

**Permission:** Admin

**Method:** POST

**Description:** save the unit

[Postman Link](https://google.com/)

### **Units Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-units-form](https://yourprojects.quarkino.io/api/modular/v1/market-units-form)

**Permission:** Administrator

**Method:** GET

**Description:** fetch the unit form

[Postman Link](https://google.com/)

### **Units Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-units-grid](https://yourprojects.quarkino.io/api/modular/v1/market-units-grid)

**Permission:** Administrator

**Method:** GET

**Description:** get market unit grid

[Postman Link](https://google.com/)

### **Market Ware Availability**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-ware-availability](https://yourprojects.quarkino.io/api/modular/v1/market-ware-availability)

**Permission:** Admin

**Method:** POST

**Description:** Change the availability of ware

[Postman Link](https://google.com/)

### **Ware Currencies**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-ware-currencies](https://yourprojects.quarkino.io/api/modular/v1/market-ware-currencies)

**Permission:** Admin

**Method:** GET

**Description:** Fetch ware currencies

[Postman Link](https://google.com/)

### **Ware Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-ware-fetch](https://yourprojects.quarkino.io/api/modular/v1/market-ware-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the ware

[Postman Link](https://google.com/)

### **Ware Quick Price Edit**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-ware-quick-price-edit](https://yourprojects.quarkino.io/api/modular/v1/market-ware-quick-price-edit)

**Permission:** Admin

**Method:** POST

**Description:** quick price edit

[Postman Link](https://google.com/)

### **Market Ware Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-ware-save](https://yourprojects.quarkino.io/api/modular/v1/market-ware-save)

**Permission:** Admin

**Method:** POST

**Description:** Save new ware

[Postman Link](https://google.com/)

### **Wares Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-wares-create](https://yourprojects.quarkino.io/api/modular/v1/market-wares-create)

**Permission:** Admin

**Method:** POST

**Description:** create wares

[Postman Link](https://google.com/)

### **Wares Save Order**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/market-wares-save-order](https://yourprojects.quarkino.io/api/modular/v1/market-wares-save-order)

**Permission:** Admin

**Method:** POST

**Description:** Save Ware Orders

[Postman Link](https://google.com/)
