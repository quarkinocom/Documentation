---
sidebar_position: 1
---

# Person
The Person feature centralizes identity verification and user management in Quarkino. It streamlines the process of managing access levels and significantly enhances performance by utilizing caching mechanisms in the database, Redis, or file layers. By encrypting user accesses with distinct keys, it ensures precise control over application layer permissions. This module is integral for managing both natural and legal entities, providing dynamic user roles and access permissions tailored to project needs.

## List of Features

- Identity Verification
- User Access Management
- Dynamic Role Assignment
- Efficient Caching for Access Control

## Usability Keys

- Simplified access control and user management.
- Enhanced system performance through efficient caching.
- Secure and encrypted user access verification.

## **Admin Endpoints**

Access with admin token.

### **Address Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-grid](https://yourprojects.quarkino.io/api/modular/v1/persons-address-grid)

**Permission:** Admin

**Method:** GET

**Description:** Address Grid View

[Postman Link](https://google.com/)

### **Address Mass Delete**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-mass-delete](https://yourprojects.quarkino.io/api/modular/v1/persons-address-mass-delete)

**Permission:** Admin

**Method:** DELETE

**Description:** Delete a Number of Addresses

[Postman Link](https://google.com/)

### **Address Save By Admin**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-save-by-admin](https://yourprojects.quarkino.io/api/modular/v1/persons-address-save-by-admin)

**Permission:** Admin

**Method:** POST

**Description:** Save the address by admin

[Postman Link](https://google.com/)

### **Admin Change Password**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-admin-change-password](https://yourprojects.quarkino.io/api/modular/v1/persons-admin-change-password)

**Permission:** Admin

**Method:** POST

**Description:** Save the new password for a user by admin

[Postman Link](https://google.com/)

### **Admin Change Password Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-admin-change-password-fetch](https://yourprojects.quarkino.io/api/modular/v1/persons-admin-change-password-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the form of the password-reset by admin

[Postman Link](https://google.com/)

### **Disable User Two Factor Authentication**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-disable-user-two-factor-authentication](https://yourprojects.quarkino.io/api/modular/v1/persons-disable-user-two-factor-authentication)

**Permission:** Admin

**Method:** PATCH

**Description:** Disable User Two Factor Authentication

[Postman Link](https://google.com/)

### **Impersonate**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-impersonate](https://yourprojects.quarkino.io/api/modular/v1/persons-impersonate)

**Permission:** Administrator

**Method:** PUT

**Description:** Get an impersonation token

[Postman Link](https://google.com/)

### **Kick Out**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-kick-out](https://yourprojects.quarkino.io/api/modular/v1/persons-kick-out)

**Permission:** Admin

**Method:** DELETE

**Description:** kick out from a particular login session.

[Postman Link](https://google.com/)

### **Kick Out Mass**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-kick-out-mass](https://yourprojects.quarkino.io/api/modular/v1/persons-kick-out-mass)

**Permission:** Admin

**Method:** DELETE

**Description:** Kick out from all sessions of a particular user, except the current one.

[Postman Link](https://google.com/)

### **Login History Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-history-grid](https://yourprojects.quarkino.io/api/modular/v1/persons-login-history-grid)

**Permission:** Admin

**Method:** GET

**Description:** get the gird of the login history of a particular user, to be used in the admin panel.

[Postman Link](https://google.com/)

### **My Login History Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-my-login-history-grid](https://yourprojects.quarkino.io/api/modular/v1/persons-my-login-history-grid)

**Permission:** Admin

**Method:** GET

**Description:** get the gird of the login history, for the current user only.

[Postman Link](https://google.com/)

### **Organizations Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-organizations-form](https://yourprojects.quarkino.io/api/modular/v1/persons-organizations-form)

**Permission:** Administrator

**Method:** GET

**Description:** fetch the Organizations Form

[Postman Link](https://google.com/)

### **Organizations Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-organizations-grid](https://yourprojects.quarkino.io/api/modular/v1/persons-organizations-grid)

**Permission:** Admin

**Method:** GET

**Description:** get Organizations grid

[Postman Link](https://google.com/)

### **Profile Fields Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-form](https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-form)

**Permission:** Administrator

**Method:** GET

**Description:** Get manageable fields for profile form

[Postman Link](https://google.com/)

### **Profile Fields Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-save](https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-save)

**Permission:** Administrator

**Method:** POST

**Description:** Save manageable fields for profile form

[Postman Link](https://google.com/)

### **Profile Fields Setting Get**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-setting-get](https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-setting-get)

**Permission:** Administrator

**Method:** GET

**Description:** Get the settings of profile fields

[Postman Link](https://google.com/)

### **Profile Fields Setting Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-setting-save](https://yourprojects.quarkino.io/api/modular/v1/persons-profile-fields-setting-save)

**Permission:** Administrator

**Method:** POST

**Description:** Save the settings of profile fields

[Postman Link](https://google.com/)

### **User Block**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-block](https://yourprojects.quarkino.io/api/modular/v1/persons-user-block)

**Permission:** Admin

**Method:** POST

**Description:** block/unblock person based on role in organization

[Postman Link](https://google.com/)

### **User Block Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-block-form](https://yourprojects.quarkino.io/api/modular/v1/persons-user-block-form)

**Permission:** Admin

**Method:** GET

**Description:** Blocking user form

[Postman Link](https://google.com/)

### **User Edit Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-form](https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-form)

**Permission:** Admin

**Method:** GET

**Description:** user edit form

[Postman Link](https://google.com/)

### **User Edit Profile**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-profile](https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-profile)

**Permission:** Admin

**Method:** POST

**Description:** edit profile

[Postman Link](https://google.com/)

### **User Panel Permits**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-permits](https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-permits)

**Permission:** Admin

**Method:** GET

**Description:** Get user permits, to be used in the panel.

[Postman Link](https://google.com/)

### **User Panel Permits Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-permits-save](https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-permits-save)

**Permission:** Admin

**Method:** PUT

**Description:** Save Permissions of a user, in a specified permit row.

[Postman Link](https://google.com/)

### **User Panel Role Assign**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-role-assign](https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-role-assign)

**Permission:** Admin

**Method:** POST

**Description:** Assign a new role to a user.

[Postman Link](https://google.com/)

### **User Panel Role Resign**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-role-resign](https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-role-resign)

**Permission:** Admin

**Method:** DELETE

**Description:** Remove an existing role from a user.

[Postman Link](https://google.com/)

### **Users Roles in Panel**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-roles](https://yourprojects.quarkino.io/api/modular/v1/persons-user-panel-roles)

**Permission:** Admin

**Method:** GET

**Description:** Get user roles, to be used in the panel.

[Postman Link](https://google.com/)

### **User Preferences Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-preferences-fetch](https://yourprojects.quarkino.io/api/modular/v1/persons-user-preferences-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Gets the form required in the panel preferences.

[Postman Link](https://google.com/)

### **User Preferences Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-preferences-save](https://yourprojects.quarkino.io/api/modular/v1/persons-user-preferences-save)

**Permission:** Admin

**Method:** POST

**Description:** Save the user preferences in the admin panel. Form is dynamic.

[Postman Link](https://google.com/)

### **User Profile Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-profile-fetch](https://yourprojects.quarkino.io/api/modular/v1/persons-user-profile-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch the profile form

[Postman Link](https://google.com/)

### **User Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-search](https://yourprojects.quarkino.io/api/modular/v1/persons-user-search)

**Permission:** Admin

**Method:** GET

**Description:** Search a user for user registration modal

[Postman Link](https://google.com/)

### **User Total Block**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-total-block](https://yourprojects.quarkino.io/api/modular/v1/persons-user-total-block)

**Permission:** Admin

**Method:** POST

**Description:** Block a user himself

[Postman Link](https://google.com/)

### **Users Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-users-grid](https://yourprojects.quarkino.io/api/modular/v1/persons-users-grid)

**Permission:** Admin

**Method:** GET

**Description:** Users Grid View

[Postman Link](https://google.com/)

### **Users Panel Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-users-panel-save](https://yourprojects.quarkino.io/api/modular/v1/persons-users-panel-save)

**Permission:** Admin

**Method:** POST

**Description:** register new user in panel

[Postman Link](https://google.com/)

### **Users Save Panel Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-users-panel-save-form](https://yourprojects.quarkino.io/api/modular/v1/persons-users-panel-save-form)

**Permission:** Admin

**Method:** GET

**Description:** user save form

[Postman Link](https://google.com/)

### **View Profile**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-view-profile](https://yourprojects.quarkino.io/api/modular/v1/persons-view-profile)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the profile view of the panel

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **Address Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-form](https://yourprojects.quarkino.io/api/modular/v1/persons-address-form)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET request designed to retrieve the address form. It requires authentication via a bearer token and aims to provide a streamlined way to fetch the address form for the user. This functionality ensures that users can access and submit their address information securely and efficiently.

[Postman Link](https://google.com/)

### **Address List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-list](https://yourprojects.quarkino.io/api/modular/v1/persons-address-list)

**Permission:** User

**Method:** GET

**Description:** The endpoint is a GET request that fetches the list of addresses associated with a user. It requires bearer token authentication to ensure secure access to the user's data. This endpoint provides a consolidated view of all user-specific address information, enabling easy management and retrieval of address details.

[Postman Link](https://google.com/)

### **Address Mark Default**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-mark-default](https://yourprojects.quarkino.io/api/modular/v1/persons-address-mark-default)

**Permission:** User

**Method:** POST

**Description:** The endpoint is a POST request that allows users to mark a specific address as their default address. It requires authentication via bearer token and accepts a JSON payload containing the hashid of the address to be set as default. This feature ensures that users can easily manage their address preferences and streamline their interactions with the platform by designating a primary address for various operations.

[Postman Link](https://google.com/)

### **Address Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-address-save](https://yourprojects.quarkino.io/api/modular/v1/persons-address-save)

**Permission:** User

**Method:** POST

**Description:** The endpoint is utilized for saving an address through a POST method. It requires bearer token authentication for security purposes. The data to be submitted includes a variety of fields such as title, contact name, division, mobile, telephone number, address, postal code, and coordinates (latitude and longitude). This functionality allows users to add or update their address details within the system.

[Postman Link](https://google.com/)

### **Change Password**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-change-password](https://yourprojects.quarkino.io/api/modular/v1/persons-change-password)

**Permission:** User

**Method:** POST

**Description:** The endpoint facilitates a secure process for users to update their account password. Requiring authentication for added security, this operation is carried out via a POST method, emphasizing user privacy and account safety by ensuring only authenticated users can make this change. This endpoint plays a crucial role in maintaining user account security and user control over their credentials.

[Postman Link](https://google.com/)

### **Change Password Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-change-password-form](https://yourprojects.quarkino.io/api/modular/v1/persons-change-password-form)

**Permission:** User

**Method:** GET

**Description:** The endpoint provides a secure method for users to access the change password form. It operates through a GET request, requiring bearer token authentication to ensure that only authorized users can fetch this form. This endpoint is essential for maintaining user account security by facilitating the process of password updates.

[Postman Link](https://google.com/)

### **Check Token**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-check-token](https://yourprojects.quarkino.io/api/modular/v1/persons-check-token)

**Permission:** User

**Method:** GET

**Description:** The endpoint, utilized through a GET request, is dedicated to verifying the validity of a user's authentication token, adding a critical layer of security to user sessions within the application. Designed to confirm that a user's session or token remains valid, this verification process is essential for maintaining secure access and operation within the system. By ensuring the authenticity and current status of user tokens, the endpoint supports secure user operations, effectively safeguarding against unauthorized access and potential security breaches. This functionality is crucial for applications that prioritize user security, providing peace of mind for both users and developers by continuously confirming the integrity of user sessions.

[Postman Link](https://google.com/)

### **Disable Two Factor Authentication**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-disable-two-factor-authentication](https://yourprojects.quarkino.io/api/modular/v1/persons-disable-two-factor-authentication)

**Permission:** User

**Method:** PATCH

**Description:** The endpoint is designed to disable the Two-Factor Authentication (2FA) feature for a user. This functionality is critical for users who wish to modify their security settings, offering them the flexibility to turn off 2FA according to their security preferences or requirements.

[Postman Link](https://google.com/)

### **Enable Two Factor Authentication**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-enable-two-factor-authentication](https://yourprojects.quarkino.io/api/modular/v1/persons-enable-two-factor-authentication)

**Permission:** User

**Method:** PATCH

**Description:** The /api/v1/persons-enable-two-factor-authentication endpoint is intended for enabling Two-Factor Authentication (2FA) for additional security. It operates through a PATCH request, underlining the platform's commitment to offering users advanced security features to safeguard their accounts effectively.

[Postman Link](https://google.com/)

### **Fetch Backup Codes**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-fetch-backup-codes](https://yourprojects.quarkino.io/api/modular/v1/persons-fetch-backup-codes)

**Permission:** User

**Method:** GET

**Description:** The endpoint is designed for retrieving backup codes, offering an additional layer of security through a GET request. This feature is essential for users who utilize two-factor authentication, providing a means to access their accounts even in scenarios where their primary authentication method is unavailable.

[Postman Link](https://google.com/)

### **Generate Sms Verification**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-generate-sms-verification](https://yourprojects.quarkino.io/api/modular/v1/persons-generate-sms-verification)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed for initiating the generation of a verification code sent via SMS. This is executed through a POST request, underscoring the platform's mechanism for enhancing security during user verification processes.

[Postman Link](https://google.com/)

### **Generate Two Factor Authentication**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-generate-two-factor-authentication](https://yourprojects.quarkino.io/api/modular/v1/persons-generate-two-factor-authentication)

**Permission:** User

**Method:** PATCH

**Description:** The endpoint, accessed via a POST request, is a vital component for bolstering user account security within applications. This endpoint facilitates the setup of two-factor authentication (2FA), an additional layer of security that requires users to provide two distinct forms of identification before gaining access to their accounts. On initiation, this process generates a unique, temporary authentication factor—often a numeric code or a time-based one-time password (TOTP)—that the user must enter alongside their regular login credentials. By incorporating this extra step, the endpoint significantly enhances the integrity and safety of user accounts, safeguarding against unauthorized access and enhancing overall platform security. This feature is especially crucial in environments where protecting sensitive user data is paramount, ensuring that only authenticated users can proceed with critical actions or access confidential information.

[Postman Link](https://google.com/)

### **Login History**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-history](https://yourprojects.quarkino.io/api/modular/v1/persons-login-history)

**Permission:** User

**Method:** GET

**Description:** The endpoint, which is called via a GET request, is designed to provide users with access to their login history on the platform. This feature is particularly important for security and account management purposes, allowing users to review their past login activities, including dates, times, and potentially the locations or devices used. By offering insights into account access patterns, this endpoint helps users identify any unusual or unauthorized access attempts, enhancing their control over account security. It serves as a crucial tool for maintaining the integrity of user accounts and personal information, reinforcing the platform's commitment to user privacy and security.

[Postman Link](https://google.com/)

### **Login Second Factor**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-second-factor](https://yourprojects.quarkino.io/api/modular/v1/persons-login-second-factor)

**Permission:** User

**Method:** PUT

**Description:** The endpoint, accessed via a PUT request, plays a critical role in the enhanced security protocols of user authentication processes. This endpoint is specifically designed for the second phase of a two-factor authentication (2FA) system, where users, after providing their standard login credentials, must verify their identity through an additional security measure. This might involve entering a code received via SMS, email, or an authentication app. The purpose of this endpoint is to validate this second factor, ensuring that the user attempting access is indeed the account holder. This step is pivotal in protecting user accounts from unauthorized access, adding an extra layer of security that significantly reduces the risk of compromise. It's a vital feature for platforms that manage sensitive user information or conduct transactions, where user trust and data security are paramount.

[Postman Link](https://google.com/)

### **Logout**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-logout](https://yourprojects.quarkino.io/api/modular/v1/persons-logout)

**Permission:** User

**Method:** POST

**Description:** The endpoint facilitates the process of logging out the current registered user from their session. This operation can target the current session or specific sessions as indicated. It is executed via a POST request, underlining the secure management of user sessions on the platform.

[Postman Link](https://google.com/)

### **Sms Verification**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-sms-verification](https://yourprojects.quarkino.io/api/modular/v1/persons-sms-verification)

**Permission:** User

**Method:** POST

**Description:** The endpoint, utilized through a POST request, is central to enhancing user security and identity verification processes within applications. This endpoint is responsible for initiating SMS verification, a critical step in confirming a user's phone number as part of account registration, login procedures, or secure transactions. By submitting a request that includes the user's phone number and potentially other identifiers, the system sends a verification code via SMS to the user's mobile device. The user must then enter this code into the application to complete the verification process, thereby proving ownership of the provided phone number. This mechanism is instrumental in preventing unauthorized account access and fraudulent activities, ensuring that sensitive actions or information access are securely gated behind a verifiable physical device owned by the user.

[Postman Link](https://google.com/)

### **Used Backup Codes**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-used-backup-codes](https://yourprojects.quarkino.io/api/modular/v1/persons-used-backup-codes)

**Permission:** User

**Method:** GET

**Description:** The endpoint provides statistics on the backup codes utilized by a user. This GET request aims to offer insights into how many backup codes have been used, ensuring users can manage their account security effectively. The successful response includes the count of used backup codes.

[Postman Link](https://google.com/)

### **User Edit Profile Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-profile-fetch](https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-profile-fetch)

**Permission:** User

**Method:** GET

**Description:** The endpoint is intended to retrieve the user profile form for editing purposes on the client side. It uses the GET method, making it straightforward for users to access their current profile information for review or modification. This endpoint plays a critical role in ensuring that users can easily manage and update their personal details within the application.

[Postman Link](https://google.com/)

### **User Edit Profile Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-profile-save](https://yourprojects.quarkino.io/api/modular/v1/persons-user-edit-profile-save)

**Permission:** User

**Method:** POST

**Description:** The endpoint is designed for persisting changes made to a user's profile on the client side. It's a crucial component of the user profile management system, enabling users to update their personal information such as names and aliases. This endpoint operates via a POST request, highlighting its role in handling data submissions to save updated user profile details securely and efficiently.

[Postman Link](https://google.com/)

## **Guest Endpoints**

Access to them without any token.

### **Get Username Fields**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-get-username-fields](https://yourprojects.quarkino.io/api/modular/v1/persons-get-username-fields)

**Permission:** Guest

**Method:** GET

**Description:** The endpoint serves a key role in customizing user interaction by providing a list of acceptable fields that can be used as usernames during user registration or identification processes. Accessed via a GET request, this endpoint ensures applications can adapt their authentication systems to accept various forms of identification, such as email addresses, phone numbers, or custom usernames. This flexibility enhances the user's ability to engage with the platform using their preferred identifiers, streamlining the login or registration process and improving the overall user experience by accommodating diverse user preferences and requirements.

[Postman Link](https://google.com/)

### **Login**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login](https://yourprojects.quarkino.io/api/modular/v1/persons-login)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint is used for user authentication on the platform. By sending a POST request, users can log in by providing their credentials, typically including a username or email address and a password. This endpoint is fundamental for securing access to the platform, ensuring that only registered and authenticated users can access their accounts and the platform's restricted features. It includes mechanisms for validating user credentials and may also support additional security measures like captcha verification or two-factor authentication (2FA) to enhance account security. This functionality is essential for maintaining user privacy and protecting sensitive information, providing a secure and reliable way for users to access their accounts.

[Postman Link](https://google.com/)

### **Login Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-form](https://yourprojects.quarkino.io/api/modular/v1/persons-login-form)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint provides the structure or layout for the user login form. Accessed via a GET request, it is designed to supply the frontend with the necessary fields and configurations required for user authentication. This might include input fields for username and password, any captcha requirements, and potentially options for social media logins or OTP (One-Time Password) authentication. The endpoint plays a critical role in dynamically rendering the login interface, accommodating various authentication methods and ensuring a user-friendly login process. It supports customization and flexibility in how authentication is handled, allowing for updates and changes without direct modifications to the frontend code. This functionality is key in maintaining a secure, accessible, and adaptable login mechanism.

[Postman Link](https://google.com/)

### **Login Request Otp**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-request-Otp](https://yourprojects.quarkino.io/api/modular/v1/persons-login-request-Otp)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is specifically designed for requesting a One-Time Password (OTP) for login purposes. It operates through a POST request and is typically used when a user opts for OTP-based authentication as an alternative to traditional password login. The user is required to submit their identification details, such as an email address or phone number, upon which the system generates and sends an OTP to the specified contact method. This OTP must then be entered in a subsequent login step to verify the user's identity. This method enhances security by providing a dynamic password that is only valid for a single session or a limited period, significantly reducing the risk of unauthorized access. It's particularly useful for users who prioritize security or for platforms that require an additional layer of authentication to protect sensitive information.

[Postman Link](https://google.com/)

### **Login Send Otp**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-send-otp](https://yourprojects.quarkino.io/api/modular/v1/persons-login-send-otp)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint is tasked with sending a One-Time Password (OTP) to a user as part of the login process. Accessed through a POST request, it requires the user to input their identification information, such as an email address or phone number, based on which the system generates and dispatches an OTP. This method is primarily used in systems that implement two-factor authentication (2FA) or OTP-based login for enhanced security. The OTP serves as a temporary password that verifies the user's identity, providing a secure layer of authentication beyond just the standard username and password. This endpoint is essential for safeguarding user accounts, especially in applications handling sensitive information, by ensuring that access is granted only to authenticated users.

[Postman Link](https://google.com/)

### **Login With Otp**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-login-with-otp](https://yourprojects.quarkino.io/api/modular/v1/persons-login-with-otp)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint is dedicated to facilitating the login process using a One-Time Password (OTP). By sending a POST request, users can authenticate their login attempt using an OTP sent to their registered email or phone number. This request typically requires the user to provide their identifier (such as email or phone number) and the OTP they received. This login method is especially useful for enhancing security through two-factor authentication (2FA) or for situations where traditional password-based login is not feasible. It is a critical component of secure account access, ensuring that only authorized users can log in by verifying their identity through a second factor. This endpoint thus supports a secure and user-friendly authentication process, accommodating users who prefer or require OTPs for login.

[Postman Link](https://google.com/)

### **Organizations Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-organizations-save](https://yourprojects.quarkino.io/api/modular/v1/persons-organizations-save)

**Permission:** admins

**Method:** POST

**Description:** save menu Organizations

[Postman Link](https://google.com/)

### **Password Reset**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery](https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint initiates the password recovery process for users. It is accessed via a POST request and typically requires the user's email address in the request body. The main function of this endpoint is to generate and send a password recovery token or link to the provided email address. This allows users who have forgotten their password or are unable to log in for other reasons to reset their password securely. Upon receiving the recovery link or token, the user can proceed to verify the token through the appropriate endpoint and set a new password. This endpoint is a critical component of user account management, ensuring that users can regain access to their accounts in a secure manner without compromising account integrity or security.

[Postman Link](https://google.com/)

### **Password Recovery Config**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery-config](https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery-config)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is designed to retrieve the configuration settings for the password recovery process. By utilizing a GET request, it enables users or systems to access the specific configurations and rules that govern how password recovery is handled, such as security requirements for passwords, the validity period of recovery tokens, and any additional steps required for verifying user identity. This endpoint is essential for providing transparency and guidance on the password recovery process, ensuring users understand the requirements and steps they need to follow to securely reset their password. It aids in streamlining the password recovery experience, minimizing user frustration by clearly outlining the process and expectations, and enhancing the overall security by enforcing best practices and guidelines.

[Postman Link](https://google.com/)

### **Password Reset Request**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery-request](https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery-request)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint initiates the password recovery process for users who have forgotten their passwords. Accessed through a POST request, it typically requires the user's email address or username to start the process. Upon receiving a request, the system generates a password recovery token or link and sends it to the user's registered email address. This allows the user to securely reset their password by verifying their identity through the token or link. This endpoint is crucial for user account security, providing a method for users to regain access to their accounts without compromising their personal information. It ensures that the password reset process is both user-friendly and secure, minimizing the risk of unauthorized access to user accounts.

[Postman Link](https://google.com/)

### **Password Reset Verify Token**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery-verify-token](https://yourprojects.quarkino.io/api/modular/v1/persons-password-recovery-verify-token)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint is designed for verifying the token received during the password recovery process for users. Accessed through a POST request, it necessitates the inclusion of the token, which is typically sent to the user's email, in the request body. The primary use of this endpoint is to validate the token's authenticity before allowing the user to proceed with setting a new password. This step is crucial for ensuring the security of the password reset process, preventing unauthorized attempts to change a user's password. It serves as a gatekeeper, confirming that the person attempting the password reset is indeed the account holder, or at least has access to the account holder's email.

[Postman Link](https://google.com/)

### **Social Login**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-social-login](https://yourprojects.quarkino.io/api/modular/v1/persons-social-login)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint enables users to log in using their social media accounts. Through a POST request, it allows for authentication via platforms like Google, or LinkedIn, simplifying the login process by leveraging existing social media credentials. This feature is particularly beneficial for users seeking a quick and hassle-free way to access the platform without the need to create and remember a separate set of login credentials. It enhances user experience by offering a convenient alternative to traditional email and password login methods. Additionally, social login can aid in gathering enriched user profiles from social media platforms, enabling more personalized and engaging user interactions on the platform.

[Postman Link](https://google.com/)

### **User Register**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-register](https://yourprojects.quarkino.io/api/modular/v1/persons-user-register)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint facilitates the registration of new users on the platform. Accessed via a POST request, it requires prospective users to submit their personal information, such as name, email, password, and potentially additional details like phone number or address, depending on the platform's requirements. This endpoint is essential for growing the platform's user base, providing a gateway for new users to create accounts and access services. It includes validation mechanisms to ensure data integrity and compliance with platform policies, such as verifying email uniqueness and password strength. This functionality is crucial for maintaining a secure and user-friendly registration process, supporting user acquisition, and ensuring a smooth onboarding experience.

[Postman Link](https://google.com/)

### **User Register Form**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/persons-user-register-form](https://yourprojects.quarkino.io/api/modular/v1/persons-user-register-form)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint provides the structure or layout for the user registration form. Accessed via a GET request, it delivers the required fields and configurations for new users to create an account on the platform. This may include input fields for personal information such as name, email, password, and potentially other details like phone number or address. The endpoint is crucial for standardizing the registration process, ensuring that all necessary information is collected in a user-friendly manner. It supports a seamless onboarding experience by dynamically presenting the registration form according to the platform's current requirements and policies, facilitating user growth and engagement by making the account creation process straightforward and accessible.

[Postman Link](https://google.com/)
