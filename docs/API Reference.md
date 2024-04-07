---
sidebar_position: 4
---

# API Reference

Quarkino’s suite of APIs provides developers with comprehensive access to a range of functionalities, from user management and content creation to e-commerce and customization. This section delves deeper into how to make the most of these APIs, with a focus on ease of access, limitations, security, and adherence to policies.

## Accessing Quarkino’s API through Postman

**Postman Collection**: Quarkino’s Postman collection serves as a practical tool for developers to explore and interact with the available APIs. It's a dynamic resource that reflects the latest changes and updates in API documentation, enabling developers to test and integrate Quarkino features seamlessly into their projects. [Access the Postman collection here](https://www.notion.so/API-Reference-5d5c8e0c5a7240d3949b514ab8d26b89?pvs=21) and set up your project’s API address to begin.

## API Call Limitations

Understanding the limitations placed on API calls is crucial for efficient application development. These limitations vary based on the selected subscription plan and the origin of the API call.

### Project API Call Limitation

The table below outlines the limitations for each subscription plan, providing clarity on the number of requests, storage, and bandwidth allocated:

| Plan | Requests/Minute | Requests/Hour | Requests/Day | Requests/Month | File Size Limit | Database Size | Bandwidth |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Basic (Free) | 300 | 1,000 | 10,000 | 250,000 | 2 GB | 500 MB | 200 GB |
| Advanced | 3,000 | 10,000 | 100,000 | 2,500,000 | 20 GB | 5,000 MB | 2,000 GB |
| Professional | 30,000 | 100,000 | 1,000,000 | 25,000,000 | 200 GB | 50,000 MB | 20,000 GB |
| Custom/Enterprise | Negotiable | Negotiable | Negotiable | Negotiable | Negotiable | Negotiable | Negotiable |

**Excess Consumption**: Projects exceeding the limit in up to two features without upgrading to the next plan are subject to overage charges, calculated based on usage.

**Project Deactivation**: Projects not accessed or without any API requests for over a year are subject to automatic deactivation, aligning with resource optimization and efficient platform use. Active engagement ensures ongoing availability.

### IP-based Limitation

API calls are also regulated based on IP, ensuring fair usage:

- **Guest Endpoints**: Up to 150 requests per minute without authentication.
- **User Endpoints**: Up to 300 requests per minute with a user token.
- **Admin Endpoints**: Up to 500 requests per minute with administrative privileges.

Special requirements for endpoint limitations may be negotiated to support unique project needs.

## Security Measures

Quarkino prioritizes security with unique encryption for each project:

- **Encryption & Authentication**: Leveraging unique keys for each project ensures the highest security level for user tokens, data encryption, and password hashing.
- **Data Integrity**: Maintains strict protocols to safeguard against unauthorized access and data breaches, offering a secure development environment.

## Policy Usage and Legal Agreement

**Usage Agreement**: Developers and project owners must adhere to Quarkino's usage policies, ensuring their applications comply with legal standards and respect copyright laws.

**Abuse and Suspension**: Projects found in violation of these policies or receiving abuse reports are subject to review and potential suspension, underscoring the importance of responsible platform use.

Adherence to these guidelines ensures a safe, productive environment for all Quarkino users, fostering innovation while maintaining legal and ethical standards.
