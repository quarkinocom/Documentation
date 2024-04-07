---
sidebar_position: 6
---

# Payment
The Payment module within Quarkino is tasked with handling all financial transactions, both online and offline, ensuring a smooth operational flow of monetary inputs and outputs throughout the system. This module is essential for integrating a variety of payment gateways, particularly catering to Iranian payment solutions, and requires configuration through the administration panel for activation.

## Features:

- **Multiple Payment Gateways**: Supports various Iranian payment gateways for comprehensive online transaction capabilities.
- **Subsystems Support**: Incorporates payment subsystems for associating transactions with specific modules or services.
- **Automatic and Manual Verification**: Offers both automatic and manual bank verification processes for online payments, including refund capabilities for issues like insufficient balance.
- **Wallet Recharge**: Enables online wallet recharging, providing users with detailed transaction histories.
- **Offline Payment Gateways**: Facilitates setting up offline payment methods such as cash, checks, and point of sale (PoS) systems, with no limit on the number of gateways.

## Usability Keys:

- **Versatile Payment Integration**: Seamless integration with multiple payment gateways for diverse transaction needs.
- **Enhanced User Experience**: Provides users with a secure and transparent view of their financial transactions and wallet status.
- **Administrative Flexibility**: Allows administrators to configure and manage payment gateways and transactions effectively.

## **Guest Endpoints**

Access to them without any token.

## **User Endpoints**

Access with user token.

## **Admin Endpoints**

Access with admin token.

### **Paths Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/payment-paths-form](https://yourprojects.quarkino.io/api/modular/v1/payment-paths-form)

**Permission:** Administrator

**Method:** GET

**Description:** fetch the paths Form

[Postman Link](https://google.com/)

### **Paths Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/payment-paths-save](https://yourprojects.quarkino.io/api/modular/v1/payment-paths-save)

**Permission:** Admin

**Method:** POST

**Description:** save paths

[Postman Link](https://google.com/)

### **User Transactions**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/payment-user-transactions](https://yourprojects.quarkino.io/api/modular/v1/payment-user-transactions)

**Permission:** Admin

**Method:** GET

**Description:** fetch the list of user's transactions

[Postman Link](https://google.com/)
