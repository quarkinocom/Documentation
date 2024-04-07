---
sidebar_position: 12
---

# Uploader
The Uploader feature streamlines file management across the Quarkino system, offering comprehensive services for file uploading, processing, and accessibility control. It facilitates diverse requirements, from displaying media in news posts to handling sensitive documents like identity proofs and resumes. This module enhances the system's flexibility by allowing the application of specific upload rules tailored to different sections, ensuring compliance with format, size, and quantity constraints. It supports advanced functionalities like image compression, alternate version generation, and SEO-friendly file metadata, making it an essential component for efficient and secure file handling in various contexts.

## List of Features

- **Flexible Upload Rules:** Define and apply customized rules for different sections, including restrictions on file size, format, and quantity.
- **Privacy and Accessibility Control:** Manage file accessibility, distinguishing between public media and private documents.
- **SEO Optimization:** Rename files and add metadata to improve SEO performance.
- **Image Processing:** Automatically generate alternate versions of images and compress files for optimized web performance.
- **Secure File Handling:** Ensure files are uploaded and stored securely, with admin capabilities for enhanced control over file management.
- **Multi-context Usability:** Use uploaded images and files in various contexts within the system, maximizing resource efficiency.

## Usability Keys

- **User-Friendly Interface:** Simplifies the process of file uploads, making it accessible to all users, regardless of technical proficiency.
- **Enhanced Security:** Incorporates measures to protect sensitive documents and ensure that files are only accessible to authorized individuals.
- **Optimized Performance:** Automatically processes images for web use, reducing load times and improving the user experience.
- **SEO Benefits:** Enhances the visibility of uploaded content through effective file naming and metadata strategies.
- **Adaptability:** Supports a wide range of use cases, from content publication to form submissions, by accommodating various file types and sizes.
- **Administrative Control:** Provides administrators with robust tools for managing upload rules and accessing detailed file information.

This structured approach to file management supports the platform's scalability and adaptability, catering to the evolving needs of content management and user interaction within the Quarkino ecosystem.

## **Guest Endpoints**

Access to them without any token.

### **Upload a File**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/uploader-upload](https://yourprojects.quarkino.io/api/modular/v1/uploader-upload)

**Permission:** Guest

**Method:** POST

**Description:** The endpoint provides a facility for users to upload files. This versatile endpoint caters to both guests and admin users, with admin-specific features enabled in the absence of a provided payload. It supports the uploading of a wide range of file types, ensuring a straightforward and secure method for users to transfer files to the server. Upon successful upload, the system responds with details of the uploaded file, including a unique ID, link to the uploaded file, and any relevant user information. This endpoint is a key component of the platform's content management and sharing capabilities, offering an essential service for storing and distributing digital content.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

## **Admin Endpoints**

Access with admin token.

### **Rule Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/uploader-rule-fetch](https://yourprojects.quarkino.io/api/modular/v1/uploader-rule-fetch)

**Permission:** Administrator

**Method:** GET

**Description:** Fetch an upload-rule form, for the use of the admin panel.

[Postman Link](https://google.com/)

### **Rule Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/uploader-rule-save](https://yourprojects.quarkino.io/api/modular/v1/uploader-rule-save)

**Permission:** Administrator

**Method:** POST

**Description:** save an upload-rule, for the use of the admin panel.

[Postman Link](https://google.com/)
