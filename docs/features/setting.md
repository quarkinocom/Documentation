---
sidebar_position: 2
---

# Setting
The Settings feature in Quarkino provides a comprehensive suite of options for administrators to customize and configure the platform to meet specific operational needs and user preferences. This feature covers a wide array of settings, from basic site information like titles and logos to more intricate configurations such as contact details, login mechanisms, and data handling policies. By offering a centralized control panel, Settings ensure that administrators can efficiently manage the application's core aspects, maintaining both functionality and brand consistency.

## List of Features

- **Site Configuration**: Customize basic site information including the site title, description, and default language.
- **Branding**: Upload and manage logos, favicons, and other branding elements to reinforce brand identity across the platform.
- **Contact Information**: Set up contact details, social media links, and other channels for user communication.
- **Login Settings**: Configure login parameters, authentication methods, and user registration options to enhance security and user experience.
- **Data Handling**: Control how data is retrieved, displayed, and managed, including settings for pagination, caching, and API access.
- **User Preferences**: Allow users to customize their interaction with the platform by setting preferred themes, notification settings, and more.
- **Public and Private Settings**: Differentiate between settings that can be publicly accessed via APIs and those restricted for administrative use.

## Usability Keys

- **Enhanced Customization**: Enables administrators to tailor the platform according to specific branding and operational requirements, ensuring a cohesive user experience.
- **Centralized Management**: Simplifies the configuration process by aggregating all settings within a single, accessible interface, reducing complexity and potential errors.
- **Security and Privacy**: Offers granular control over authentication and data handling practices, reinforcing the platform's security posture and user trust.
- **Flexibility and Scalability**: Accommodates a wide range of customization needs, from small tweaks to major overhauls, supporting the platform's growth and evolution.

## **Admin Endpoints**

Access with admin token.

### **Fetch Entry**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/setting-fetch](https://yourprojects.quarkino.io/api/modular/v1/setting-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the form binder of an entry, together with her current value(s).

[Postman Link](https://google.com/)

### **List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/setting-list](https://yourprojects.quarkino.io/api/modular/v1/setting-list)

**Permission:** Admin

**Method:** GET

**Description:** Get all available setting entries across all modules with their category, title and group.

[Postman Link](https://google.com/)

### **Reset Settings**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/setting-reset](https://yourprojects.quarkino.io/api/modular/v1/setting-reset)

**Permission:** Admin

**Method:** DELETE

**Description:** reset the data of an entry, and returns the new default set. This is for admin panel only.

[Postman Link](https://google.com/)

### **Set**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/setting-set](https://yourprojects.quarkino.io/api/modular/v1/setting-set)

**Permission:** Admin

**Method:** PUT

**Description:** set a setting value

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

There isn’t any API for user access

## **Guest Endpoints**

Access to them without any token.

### **Get**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/setting-get](https://yourprojects.quarkino.io/api/modular/v1/setting-get)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is designed to retrieve system or user-specific settings. It can be accessed via a GET request, often without requiring any parameters, or it might accept identifiers or keys to fetch specific settings. The primary function of this endpoint is to provide a centralized method for retrieving configuration details, preferences, or other setting-related data that influence the behavior or appearance of the application. It's crucial for maintaining a customizable user experience, allowing for adjustments to be made based on user or system requirements. This endpoint supports both the operational needs of the application by enabling dynamic configuration changes and the personalization preferences of the user, ensuring a tailored application environment.

[Postman Link](https://google.com/)
