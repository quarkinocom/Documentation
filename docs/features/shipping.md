---
sidebar_position: 7
---

# Shipping
Shipping methods encompass a wide array of rules including permissible regions, shipping costs, volume or weight limitations, acceptable timeframes, and specific days or intervals for shipping. Administrators can meticulously configure these parameters to tailor the shipping methods according to the unique needs of the business, ensuring a seamless order registration process.

## Key Features

- **Diverse Shipping Rules**: Incorporate rules based on cities, provinces, costs, and more to accommodate different shipping requirements.
- **Dynamic Configuration**: Administrators have the flexibility to set up shipping methods with all necessary parameters.
- **Capacity Allocation**: Allocate specific capacities for each time interval, monitoring availability during order placement.
- **Cost Calculation**: Offers the option to calculate transportation costs as either a fixed amount or based on the order amount.
- **Order-Related Fields**: Supports additional fields for storing shipping-related data for each order.

## Usability Keys

- **Versatile Shipping Management**: Adapt shipping strategies to align with business operations and customer expectations.
- **Enhanced Customer Satisfaction**: Provide customers with clear, customizable shipping options to improve the overall shopping experience.
- **Operational Efficiency**: Streamline the order-to-shipment process with automated rules and cost calculations.
- **Data-Driven Insights**: Utilize shipping data to optimize logistics, reduce costs, and improve service quality.

The Shipping Methods module represents a crucial component in the architecture of Quarkino's e-commerce capabilities, allowing for the intricate management of physical goods' delivery in a way that is both user-friendly and business-efficient.

## **Guest Endpoints**

Access to them without any token.

## **User Endpoints**

Access with user token.

## **Admin Endpoints**

Access with admin token.

### **Method Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/shipping-method-fetch](https://yourprojects.quarkino.io/api/modular/v1/shipping-method-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the shipping method

[Postman Link](https://google.com/)

### **Method Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/shipping-method-save](https://yourprojects.quarkino.io/api/modular/v1/shipping-method-save)

**Permission:** Admin

**Method:** POST

**Description:** save a shipping method

[Postman Link](https://google.com/)

### **Rule Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/shipping-rule-fetch](https://yourprojects.quarkino.io/api/modular/v1/shipping-rule-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the form-binder of a rule, both existing in the method or a new one.

[Postman Link](https://google.com/)

### **Rule Remove**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/shipping-rule-remove](https://yourprojects.quarkino.io/api/modular/v1/shipping-rule-remove)

**Permission:** Admin

**Method:** DELETE

**Description:** Remove a rule, from a method.

[Postman Link](https://google.com/)

### **Rule Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/shipping-rule-save](https://yourprojects.quarkino.io/api/modular/v1/shipping-rule-save)

**Permission:** Admin

**Method:** POST

**Description:** Save a rule, both for updating an existing one or inserting a new one.

[Postman Link](https://google.com/)
