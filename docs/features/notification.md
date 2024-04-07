---
sidebar_position: 10
---

# Notification
The Notification module is an essential component in enhancing user engagement and communication within the Quarkino platform. It offers a comprehensive solution for sending various types of notifications, such as SMS, email, push notifications, and database entries, ensuring users stay informed about significant events and updates. By supporting multiple notification drivers and languages, it provides a flexible and personalized communication strategy that meets the diverse needs of users and administrators alike.

## List of Features

- **Multi-Channel Support**: Enables notifications through various channels including SMS, email, push notifications, and database entries.
- **Custom Notification Drivers**: Allows for the definition and utilization of different drivers to cater to specific notification needs.
- **Language Support**: Supports active languages, delivering notifications in the user's preferred language based on their profile settings.
- **Event-Triggered Notifications**: Automatically sends relevant notifications for critical events within the system, such as login activities, account changes, order updates, and more.
- **User and Admin Notifications**: Provides separate access and configurations for both users and administrators, tailoring notification delivery to different audiences.
- **Flexible Notification Management**: Offers the ability to configure each notification through various channels and custom drivers, enhancing the effectiveness of the notification strategy.

## Usability Keys

- **Enhanced User Engagement**: Keeps users engaged and informed by delivering timely and relevant notifications directly to their preferred channel.
- **Personalized Communication**: Offers personalized notification experiences by supporting multiple languages and allowing users to receive notifications in their preferred language.
- **Operational Efficiency**: Streamlines communication by automating the delivery of notifications for critical system events, reducing manual effort and ensuring prompt information dissemination.
- **Adaptable Strategy**: The flexibility to use custom drivers and configure notifications per event or user preference allows for an adaptable communication strategy that can evolve with the platform's needs.
- **Improved User Experience**: By providing comprehensive notification management tools for administrators and clear, informative notifications for users, the module significantly enhances the overall user experience on the platform.

This approach to notification management ensures that the Quarkino platform can maintain a high level of user engagement, satisfaction, and operational efficiency.

## **Guest Endpoints**

Access to them without any token.

### **Browser Paths List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-browser-paths-list](https://yourprojects.quarkino.io/api/modular/v1/notifier-browser-paths-list)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is designed to list the available browser paths for notifications. By issuing a GET request, it allows users or systems to retrieve a structured list of paths where notifications can be sent or displayed within the browser. This could include specific URLs, sections of a website, or app components that are configured to show notifications. The purpose of this endpoint is to facilitate the management and targeting of browser-based notifications, ensuring that notifications are relevant and delivered in the contextually appropriate area of the user interface. It supports the customization and optimization of notification strategies, enhancing user engagement by delivering timely and relevant information directly within the browser environment.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **User Notifications**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notifications](https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notifications)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET method designed to retrieve the notifications (SMS or email) for a customer. This endpoint allows users to access their notifications, providing them with updates or information related to their account or activities. It's particularly useful for ensuring users stay informed about relevant events, offers, or any other significant information delivered through SMS or email notifications.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.

### **Fetch Path**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-fetch-path](https://yourprojects.quarkino.io/api/modular/v1/notifier-fetch-path)

**Permission:** Admin

**Method:** GET

**Description:** fetch the form required to create a new path or edit an existing one.

[Postman Link](https://google.com/)

### **Fetch Path Configs**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-fetch-path-configs](https://yourprojects.quarkino.io/api/modular/v1/notifier-fetch-path-configs)

**Permission:** Admin

**Method:** GET

**Description:** fetch the form required to configure a driver.

[Postman Link](https://google.com/)

### **Mass Notification Config Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-mass-notification-config-form](https://yourprojects.quarkino.io/api/modular/v1/notifier-mass-notification-config-form)

**Permission:** Admin

**Method:** GET

**Description:** fetch the form of config collectively

[Postman Link](https://google.com/)

### **Mass Notification Config Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-mass-notification-config-save](https://yourprojects.quarkino.io/api/modular/v1/notifier-mass-notification-config-save)

**Permission:** Admin

**Method:** POST

**Description:** save the mass config notification

[Postman Link](https://google.com/)

### **My Notifications**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-my-notifications](https://yourprojects.quarkino.io/api/modular/v1/notifier-my-notifications)

**Permission:** Admin

**Method:** GET

**Description:** get database notifications for admin

[Postman Link](https://google.com/)

### **Notification Config Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-notification-config-fetch](https://yourprojects.quarkino.io/api/modular/v1/notifier-notification-config-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the form required to receive notification config from an admin.

[Postman Link](https://google.com/)

### **Notification Config Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-notification-config-save](https://yourprojects.quarkino.io/api/modular/v1/notifier-notification-config-save)

**Permission:** Admin

**Method:** POST

**Description:** Save the config of a particular notification.

[Postman Link](https://google.com/)

### **Notifier Class Update**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-notifier-class-update](https://yourprojects.quarkino.io/api/modular/v1/notifier-notifier-class-update)

**Permission:** Administrator

**Method:** POST

**Description:** update notifications based on enable modules

[Postman Link](https://google.com/)

### **Save Path**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-save-path](https://yourprojects.quarkino.io/api/modular/v1/notifier-save-path)

**Permission:** Admin

**Method:** POST

**Description:** create a new path or edit an existing one.

[Postman Link](https://google.com/)

### **Save Path Configs**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-save-path-configs](https://yourprojects.quarkino.io/api/modular/v1/notifier-save-path-configs)

**Permission:** Admin

**Method:** PUT

**Description:** save the data required to configure a driver.

[Postman Link](https://google.com/)

### **User Notification Management**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notification-management](https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notification-management)

**Permission:** Admin

**Method:** POST

**Description:** enable or de active notification

[Postman Link](https://google.com/)

### **User Notifications Count**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notifications-count](https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notifications-count)

**Permission:** Admin

**Method:** GET

**Description:** get the number of unread notifications

[Postman Link](https://google.com/)

### **User Notifications List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notifications-list](https://yourprojects.quarkino.io/api/modular/v1/notifier-user-notifications-list)

**Permission:** Admin

**Method:** GET

**Description:** get the list of user notifications

[Postman Link](https://google.com/)
