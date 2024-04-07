---
sidebar_position: 8
---

# Wallet
The Wallet feature in Quark enables comprehensive financial transactions and management for users. Offering versatile wallet functionality, it supports multiple currencies and allows for the infinite creation of wallets per user or organization. It enables users to increase balance, block funds, and perform transactions seamlessly within the Quark ecosystem.

## List of Features

- **Multi-currency Support:** Ability to create and manage wallets in different currencies.
- **Transaction Management:** Monitor and manage all financial transactions, including deposits, withdrawals, and balance adjustments.
- **Balance Management:** Users can check their wallet balances, recharge online, and block/unblock funds as needed.
- **Wallet Transactions:** Detailed transaction history for user review and financial management.
- **Integration with Other Modules:** Wallet functionalities can be expanded or utilized by other modules within Quark, enhancing the overall ecosystem.

## Usability Keys

- **User-Friendly Interface:** Simplifies the process of wallet management for users, enhancing the overall user experience.
- **Flexible Financial Transactions:** Offers a wide range of transactional capabilities, from simple balance checks to complex financial operations.
- **Secure and Reliable:** Ensures the security of user funds and transactions, building trust within the Quark ecosystem.
- **Seamless Integration:** Easily integrates with other Quark modules, providing a cohesive financial management solution.

## **Guest Endpoints**

Access to them without any token.

## **User Endpoints**

Access with user token.

### **My Wallets**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-my-wallets](https://yourprojects.quarkino.io/api/modular/v1/wallet-my-wallets)

**Permission:** User

**Method:** GET

**Description:** The endpoint, accessed through a GET request, is integral to financial and transactional platforms, serving as a gateway for users to view and manage their personal wallet or account information. This endpoint provides a user-friendly overview of the user's financial assets within the platform, including balances, transaction history, and potentially other wallet-related functionalities. It is designed to offer users a comprehensive snapshot of their financial standing within the application, enabling them to make informed decisions about future transactions, investments, or transfers. By ensuring easy access to critical financial data, this endpoint plays a crucial role in enhancing user engagement and trust in the platform's financial services, making it easier for users to navigate their financial landscape and interact with various features of the application.

[Postman Link](https://google.com/)

### **Online Charge**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-online-charge](https://yourprojects.quarkino.io/api/modular/v1/wallet-online-charge)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed to facilitate the process of adding funds to a user's wallet through an online transaction. Utilizing a POST method, it ensures a secure mechanism for users to charge their wallets. This functionality is part of the Wallet services, allowing users to manage their financial transactions within the platform efficiently. On successful execution, the system confirms the transaction, enhancing the user experience by providing a seamless and reliable method for managing wallet balances.

[Postman Link](https://google.com/)

### **Online Gates**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-online-gates](https://yourprojects.quarkino.io/api/modular/v1/wallet-online-gates)

**Permission:** User

**Method:** GET

**Description:** The endpoint is dedicated to providing a comprehensive list of available online payment gateways. This GET request is designed to offer users insight into the various online payment options accessible for transactions, enhancing the flexibility and convenience of managing financial activities within the platform. Aimed at users seeking to understand their online payment alternatives, this endpoint ensures that all necessary information about each gateway, including supported currencies and gateway details, is readily available.

[Postman Link](https://google.com/)

### **Transactions List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-transactions-list](https://yourprojects.quarkino.io/api/modular/v1/wallet-transactions-list)

**Permission:** User

**Method:** GET

**Description:** The endpoint is designed to provide a list of wallet transactions. It is structured to handle GET requests, aiming to fetch and list transactions associated with a wallet. This endpoint serves as a crucial part of the API, enabling the retrieval of transactional data which is essential for monitoring and managing financial activities within the application.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.

### **Block Amounts**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-blocked-amounts](https://yourprojects.quarkino.io/api/modular/v1/wallet-blocked-amounts)

**Permission:** Admin

**Method:** POST

**Description:** save blocked_amounts

[Postman Link](https://google.com/)

### **Blocked Amounts Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-blocked-amounts-form](https://yourprojects.quarkino.io/api/modular/v1/wallet-blocked-amounts-form)

**Permission:** Admin

**Method:** GET

**Description:** fetch the blocked_amounts Form

[Postman Link](https://google.com/)

### **Combo**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-combo](https://yourprojects.quarkino.io/api/modular/v1/wallet-combo)

**Permission:** Admin

**Method:** GET

**Description:** get the list of wallets, to be used in a combo selector, powered by a handy search engine.

[Postman Link](https://google.com/)

### **Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-form](https://yourprojects.quarkino.io/api/modular/v1/wallet-form)

**Permission:** Administrator

**Method:** GET

**Description:** fetch the wallets Form

[Postman Link](https://google.com/)

### **Owners List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-owners-list](https://yourprojects.quarkino.io/api/modular/v1/wallet-owners-list)

**Permission:** Admin

**Method:** GET

**Description:** get users or organizations list

[Postman Link](https://google.com/)

### **Processing Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-processing-fetch](https://yourprojects.quarkino.io/api/modular/v1/wallet-processing-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch processing form of wallet

[Postman Link](https://google.com/)

### **Processing Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-processing-save](https://yourprojects.quarkino.io/api/modular/v1/wallet-processing-save)

**Permission:** Admin

**Method:** POST

**Description:** Save processing system of wallets

[Postman Link](https://google.com/)

### **Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-save](https://yourprojects.quarkino.io/api/modular/v1/wallet-save)

**Permission:** Admin

**Method:** POST

**Description:** save wallet

[Postman Link](https://google.com/)

### **Wallet Deposit Change Status**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposit-change-status](https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposit-change-status)

**Permission:** Admin

**Method:** POST

**Description:** Change wallet deposit status

[Postman Link](https://google.com/)

### **Wallet Deposit Change Status Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposit-change-status-form](https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposit-change-status-form)

**Permission:** Admin

**Method:** GET

**Description:** Fetch Wallet Deposit change status form.

[Postman Link](https://google.com/)

### **WalletDeposits Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposits-form](https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposits-form)

**Permission:** Admin

**Method:** GET

**Description:** fetch the wallet_deposits Form

[Postman Link](https://google.com/)

### **WalletDeposits Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposits-save](https://yourprojects.quarkino.io/api/modular/v1/wallet-wallet-deposits-save)

**Permission:** Admin

**Method:** POST

**Description:** save wallet_deposits

[Postman Link](https://google.com/)
