---
sidebar_position: 9
---

# Subscription
The Subscription feature within Quarkino enhances user engagement and revenue streams through a flexible and comprehensive subscription management framework. This feature is essential for businesses and platforms aiming to offer services or content on a subscription basis, catering to a wide range of user needs with customizable packages.

## List of Features

- **Diverse Subscription Packages:** Support for creating various types of subscription packages, including volume-based, time-based, or a combination of features.
- **Flexible Payment Integration:** Ability to associate specific payment gateways with individual subscription packages or groups for tailored financial arrangements.
- **User Engagement Notifications:** Functionality to activate notifications related to the subscription lifecycle, enhancing user experience and engagement.
- **Dynamic Subscription Management:** Tools for users to purchase, administrators to review, and the automatic activation of reserved subscription packages.
- **Comprehensive Configuration Settings:** Extensive settings to accommodate different configurations and usage types for subscription packages.
- **Future Expansion Support:** Design consideration for future features integration, such as shipping methods and delivery timelines, to enrich the subscription service offerings.

## Usability Keys

- **Enhanced User Experience:** Offers users the flexibility to choose from a variety of subscription packages that best suit their needs, enhancing satisfaction and loyalty.
- **Streamlined Subscription Management:** Enables administrators to efficiently manage and review subscription packages, simplifying operational workflows.
- **Increased Revenue Opportunities:** Provides a structured platform for selling subscription services, opening up new revenue streams for businesses.
- **Customizable Service Delivery:** Supports diverse business models with customizable subscription packages, meeting the varied needs of different user segments.
- **Automated Subscription Lifecycle:** Automates critical aspects of the subscription lifecycle, including renewals and notifications, ensuring continuous service delivery without manual intervention.

## **Guest Endpoints**

Access to them without any token.

### **My Order Coupon Inquiry**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-my-order-coupon-inquiry](https://yourprojects.quarkino.io/api/modular/v1/subscription-my-order-coupon-inquiry)

**Permission:** Order

**Method:** GET

**Description:** Evaluate the given discount coupons and give the result, without affecting the prices.

[Postman Link](https://google.com/)

### **Package Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-package-fetch](https://yourprojects.quarkino.io/api/modular/v1/subscription-package-fetch)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is designed for retrieving details about subscription packages. Accessed via a GET request, it allows users or systems to query and receive information on available subscription options, including pricing, duration, and included features or services. This endpoint is essential for displaying subscription choices to users, enabling them to make informed decisions about which package best suits their needs. It might also support filtering or sorting parameters to customize the retrieval of subscription packages based on specific criteria, such as price range or feature set. This functionality is key in facilitating a smooth user experience for those looking to subscribe or change their subscription plan, ensuring that all necessary information is accessible and easy to understand.

[Postman Link](https://google.com/)

### **Packages List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-packages-list](https://yourprojects.quarkino.io/api/modular/v1/subscription-packages-list)

**Permission:** Guest

**Method:** GET

**Description:** The endpoint is crafted to showcase the subscription packages available within a specific category. Accessible via a GET request, it allows both guests and registered users to browse through various subscription options by specifying the category through either a hash ID or slug. This functionality enriches the user experience by offering a curated list of subscription packages tailored to their interests or needs within the platform, fostering an environment where users can easily find and subscribe to services that best suit their preferences.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **My Orders**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-my-orders](https://yourprojects.quarkino.io/api/modular/v1/subscription-my-orders)

**Permission:** User

**Method:** GET

**Description:** The endpoint, accessible via a GET request, is specifically designed for users to view their own subscription-related orders within a platform. This endpoint caters to users who wish to track their subscription statuses, view past orders, and manage their ongoing subscriptions. By providing a comprehensive overview of all subscription orders made by the user, including details such as order dates, amounts, statuses, and subscription periods, it empowers users to manage their subscriptions effectively. This functionality is crucial for platforms offering subscription services, as it enhances user experience by offering transparency and control over subscription management, thereby fostering trust and loyalty among the user base.

[Postman Link](https://google.com/)

### **Order Finalize**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-order-finalize](https://yourprojects.quarkino.io/api/modular/v1/subscription-order-finalize)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed for the final step in the order process, focusing on finalizing orders. It utilizes the POST method to ensure that all necessary details for completing an order are securely submitted and processed. This endpoint is essential for effectively concluding transactions, capturing final order details, and transitioning orders to their completion state.

[Postman Link](https://google.com/)

### **Order Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-order-save](https://yourprojects.quarkino.io/api/modular/v1/subscription-order-save)

**Permission:** User

**Method:** POST

**Description:** The endpoint enables the saving of orders within the admin panel. It operates through a POST method, allowing for the detailed handling and recording of order transactions. This endpoint plays a vital role in the order management process, offering a streamlined method for administrators to update or store order information effectively.

[Postman Link](https://google.com/)

### **Payment Offline Transaction Make**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-payment-offline-transaction-make](https://yourprojects.quarkino.io/api/modular/v1/subscription-payment-offline-transaction-make)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed to facilitate the creation of offline payment transactions. Utilizing a POST method, it allows for the submission of necessary transaction details such as identification, amount, tracking number, date of effect, path identifier, and receipt information directly to the server. This endpoint serves as a key component in managing offline payments, ensuring a seamless integration of such transactions into the system's broader financial operations.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.

### **Category Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-category-fetch](https://yourprojects.quarkino.io/api/modular/v1/subscription-category-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the category

[Postman Link](https://google.com/)

### **Category List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-category-list](https://yourprojects.quarkino.io/api/modular/v1/subscription-category-list)

**Permission:** Admin

**Method:** GET

**Description:** the list of categories

[Postman Link](https://google.com/)

### **Category Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-category-save](https://yourprojects.quarkino.io/api/modular/v1/subscription-category-save)

**Permission:** Admin

**Method:** POST

**Description:** save the subscription's category

[Postman Link](https://google.com/)

### **General Settings Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-general-settings-fetch](https://yourprojects.quarkino.io/api/modular/v1/subscription-general-settings-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the general settings

[Postman Link](https://google.com/)

### **General Settings Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-general-settings-save](https://yourprojects.quarkino.io/api/modular/v1/subscription-general-settings-save)

**Permission:** Admin

**Method:** POST

**Description:** save the settings

[Postman Link](https://google.com/)

### **Mass Action Package Edit**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-mass-action-package-edit](https://yourprojects.quarkino.io/api/modular/v1/subscription-mass-action-package-edit)

**Permission:** Admin

**Method:** POST

**Description:** edit the group of package

[Postman Link](https://google.com/)

### **Package Fetch Panel**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-package-fetch-panel](https://yourprojects.quarkino.io/api/modular/v1/subscription-package-fetch-panel)

**Permission:** Admin

**Method:** GET

**Description:** fetch the package for admin in panel

[Postman Link](https://google.com/)

### **Package Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-package-save](https://yourprojects.quarkino.io/api/modular/v1/subscription-package-save)

**Permission:** Admin

**Method:** POST

**Description:** save the package

[Postman Link](https://google.com/)

### **Seller Info Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-seller-info-fetch](https://yourprojects.quarkino.io/api/modular/v1/subscription-seller-info-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the seller info

[Postman Link](https://google.com/)

### **Seller Info Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/subscription-seller-info-save](https://yourprojects.quarkino.io/api/modular/v1/subscription-seller-info-save)

**Permission:** Admin

**Method:** POST

**Description:** save the seller info in setting

[Postman Link](https://google.com/)
