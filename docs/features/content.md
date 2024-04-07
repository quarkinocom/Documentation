---
sidebar_position: 3
---

# Content
The Content module is pivotal to Quarkino's ecosystem, offering robust management and presentation tools for a wide array of content types. It serves as the backbone for all content-related activities on the platform, enabling administrators to craft, categorize, and curate content that ranges from educational materials and news articles to galleries and customer testimonials. With its versatile settings and configurations, the Content module ensures that content across the platform is both engaging and well-organized, catering to the diverse needs of its audience.

## List of Features

- **Dynamic Content Types**: Supports a broad spectrum of content types including blogs, FAQs, news, tutorials, downloadable content, services, and more.
- **Content Customization**: Provides a suite of customizable elements for each content piece, such as titles, subtitles, body texts, summaries, categories, tags, images, and attachments.
- **Advanced Presentation Options**: Integrates with the Content Themes module to offer specialized templates and designs for different types of content, enhancing the overall presentation and user experience.
- **Comprehensive Management Tools**: Features include publication scheduling, visibility settings, editor assignments, sharing options, and short links for ease of content distribution and access control.
- **Interoperability with Other Modules**: Allows for seamless integration with other Quarkino modules, facilitating the addition of functionalities like likes/dislikes, comments, or social media sharing to content items.

## Usability Keys

- **Enhanced User Engagement**: By enabling the creation of varied and rich content, the module plays a crucial role in attracting and retaining the platform's audience.
- **Efficiency in Content Management**: Offers streamlined workflows for content creation and maintenance, reducing the administrative burden and allowing for quick updates and edits.
- **Flexibility and Scalability**: Accommodates evolving content needs and preferences, ensuring the platform can grow and adapt without compromising content quality or user experience.
- **Consistency and Branding**: Ensures that all content reflects the platform's branding and style guidelines, maintaining a consistent and professional appearance across all touchpoints.

## **Guest Endpoints**

Access to them without any token.

### **Features**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-features](https://yourprojects.quarkino.io/api/modular/v1/content-features)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is designed to provide a list of featured content available on the platform. Through a GET request, users can access a curated selection of content that is highlighted for its relevance, popularity, or quality. This could include articles, videos, products, or any other form of content that the platform wishes to emphasize. The purpose of this endpoint is to enhance user engagement by directing attention to standout content, facilitating discovery and exploration. It supports the platform's content strategy by promoting key items, thereby increasing visibility and interaction with selected content. This functionality is crucial for platforms looking to showcase premium or timely content to their audience, encouraging deeper user involvement.

[Postman Link](https://google.com/)

### **Post Lists**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-lists](https://yourprojects.quarkino.io/api/modular/v1/content-post-lists)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint is designed to retrieve lists of posts based on specified criteria or filters. Accessed via a GET request, it allows users to query for posts by categories, tags, authorship, publication status, or other relevant filters. This endpoint is essential for content discovery and navigation within the platform, enabling users to easily find posts that match their interests or information needs. It supports dynamic content presentation, such as displaying the latest posts, featured content, or tailored recommendations. By providing a flexible and efficient way to access a variety of posts, this endpoint enhances the user experience, encouraging exploration and engagement with the content.

[Postman Link](https://google.com/)

### **Post Single**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-single](https://yourprojects.quarkino.io/api/modular/v1/content-post-single)

**Permission:** Guest

**Method:** GET

**Description:** The endpoint, accessible through a GET request, is crafted to fetch a specific post by leveraging unique identifiers such as a post's hashid or slug. It is an essential tool in content-driven applications, offering the capability to retrieve detailed information about a single piece of content from a vast repository. This endpoint caters to a broad audience, including guest users, allowing for a wide accessibility range. The flexibility in query parameters, including type, locale, including, and excluding, enriches the customization of the data retrieval process, enabling a tailored response that meets varied consumer needs. This endpoint not only streamlines access to individual content pieces but also enhances the overall content consumption experience by providing targeted, detailed information with efficiency and precision.

[Postman Link](https://google.com/)

### **Post Visit**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-visit](https://yourprojects.quarkino.io/api/modular/v1/content-post-visit)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint is utilized for recording visits to specific posts. Through a POST request, it captures user engagement with content by logging visits or views. This information is crucial for understanding content popularity, user engagement levels, and for analytics purposes such as measuring reach and impact. It typically requires the unique identifier of the post being visited as part of the request. This functionality supports content creators and platform administrators by providing insights into which posts are attracting the most attention, aiding in content strategy adjustments and enhancing the overall content offering based on user interest and interaction patterns.

[Postman Link](https://google.com/)

### **Posts Archive Overview**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-posts-archive-overview](https://yourprojects.quarkino.io/api/modular/v1/content-posts-archive-overview)

**Permission:** Guest

**Method:** GET

**Description:** The endpoint, utilized via a GET request, is specifically designed to offer a comprehensive overview of archived posts within a platform. This endpoint is pivotal for applications that manage a significant volume of content, such as blogs, news portals, or content repositories, by providing an organized summary of archived materials. It facilitates easy navigation and exploration of historical content, enabling users to access a curated selection of posts based on various archival parameters. By supporting enhanced searchability and accessibility of past content, this endpoint significantly contributes to the user's ability to discover, engage with, and reflect on content over time, thereby enriching the overall content exploration experience on the platform.

[Postman Link](https://google.com/)

### **Templates**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-templates](https://yourprojects.quarkino.io/api/modular/v1/content-templates)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint provides access to a collection of content templates. It is accessed through a GET request, enabling users or content creators to retrieve predefined templates for various types of content, such as articles, blogs, reports, or social media posts. These templates are designed to streamline the content creation process, offering structured layouts and formatting guidelines that users can follow to maintain consistency and quality across their content. The endpoint is particularly useful for platforms that support content creation and publication, as it assists users in quickly generating new content while adhering to established standards and styles. This functionality enhances the user experience by simplifying content production and ensuring that all content meets the platform's requirements.

[Postman Link](https://google.com/)

### **Donate**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-donate](https://yourprojects.quarkino.io/api/modular/v1/content-themes-donate)

**Permission:** Guest

**Method:** POST

**Description:** The endpoint is a pivotal feature for platforms that enable users to support content creators or themes through financial donations, accessible via a POST request. This functionality allows guests or registered users to make contributions by specifying a content post's hashid, the donation amount, and optionally, the donor's name and mobile number. This process not only facilitates the creation of a donation document but also initiates a posting process that culminates in providing the donor with a callback URL for payment processing. Designed to streamline the donation experience, this endpoint supports the platform's ecosystem by encouraging community engagement and financial support, thereby ensuring content creators or thematic projects receive the necessary backing to continue their creative or thematic endeavors.

[Postman Link](https://google.com/)

### **Faq List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-list](https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-list)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint provides access to a list of frequently asked questions (FAQs) related to specific content themes. Utilizing a GET request, it enables users to retrieve a curated list of FAQs designed to assist in understanding or navigating particular themes or topics within the platform. This resource is invaluable for users seeking immediate answers to common queries, enhancing user support without direct intervention. It likely supports various filtering or sorting options, allowing users to quickly find the most relevant FAQs based on their interests or needs. This endpoint plays a crucial role in self-service user support, reducing the need for contacting customer service and improving the overall user experience by providing instant access to critical information and guidance.

[Postman Link](https://google.com/)

### **Slideshows List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-slideshows-list](https://yourprojects.quarkino.io/api/modular/v1/content-themes-slideshows-list)

**Permission:** Guest

**Method:** GET

**Description:** This endpoint provides a list of slideshows related to specific content themes. Through a GET request, it allows users to access curated slideshows that are organized based on various themes, topics, or categories. These slideshows might include a series of images, videos, or text-based slides designed to inform, educate, or entertain the audience. This functionality is especially useful for platforms aiming to enhance user engagement through visually appealing and thematic content presentations. It supports content creators and curators in showcasing their work in a structured and interactive format, potentially increasing content consumption and user retention by offering an immersive browsing experience.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **Post Fave**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-fave](https://yourprojects.quarkino.io/api/modular/v1/content-post-fave)

**Permission:** User

**Method:** PUT

**Description:** The endpoint is a PUT method designed to add or remove a given post to or from the favorite lists of an online user. This endpoint allows users to manage their favorite content easily, enabling them to mark posts as favorites for quick access later or remove them from their favorites list. This functionality enhances user engagement with the content by simplifying how users keep track of their preferred posts.

[Postman Link](https://google.com/)

### **Update Visits**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-update-visits](https://yourprojects.quarkino.io/api/modular/v1/content-update-visits)

**Permission:** User

**Method:** POST

**Description:** The endpoint is tailored for tracking user interactions with content, specifically by updating the visit count for pages after a user has logged in. This POST request enables the system to accurately monitor and record the engagement levels of different pieces of content, ensuring that user interactions are captured and analyzed for content optimization and user experience improvements. Through this endpoint, the platform can refine content recommendations and insights based on actual user engagement.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.

### **Organizations List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-organizations-list](https://yourprojects.quarkino.io/api/modular/v1/content-organizations-list)

**Permission:** Admin

**Method:** GET

**Description:** Get a list of organizations

[Postman Link](https://google.com/)

### **Post Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-post-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Post Fetch

[Postman Link](https://google.com/)

### **Post Fetch Buttons**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-fetch-buttons](https://yourprojects.quarkino.io/api/modular/v1/content-post-fetch-buttons)

**Permission:** Admin

**Method:** GET

**Description:** Fetch enough data to refresh the buttons area of the post editor

[Postman Link](https://google.com/)

### **Post Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-grid](https://yourprojects.quarkino.io/api/modular/v1/content-post-grid)

**Permission:** Admin

**Method:** GET

**Description:** Post Grid View

[Postman Link](https://google.com/)

### **Post Minimal Destroy**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-destroy](https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-destroy)

**Permission:** Admin

**Method:** DELETE

**Description:** destroys a set of minimal posts of a single sisterhood in all language the admin has access.

[Postman Link](https://google.com/)

### **Post Minimal Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch the form-binder of a minimal post.

[Postman Link](https://google.com/)

### **Post Minimal Restore**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-restore](https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-restore)

**Permission:** Admin

**Method:** PUT

**Description:** undelete a set of minimal posts of a single sisterhood in all language the admin has access.

[Postman Link](https://google.com/)

### **Post Minimal Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-save](https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-save)

**Permission:** Admin

**Method:** POST

**Description:** Save a minimal post.

[Postman Link](https://google.com/)

### **Post Minimal Trash**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-trash](https://yourprojects.quarkino.io/api/modular/v1/content-post-minimal-trash)

**Permission:** Admin

**Method:** DELETE

**Description:** soft-delete a set of minimal posts of a single sisterhood in all language the admin has access.

[Postman Link](https://google.com/)

### **Post Pin**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-pin](https://yourprojects.quarkino.io/api/modular/v1/content-post-pin)

**Permission:** Admin

**Method:** POST

**Description:** Content post pin

[Postman Link](https://google.com/)

### **Post Quick View**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-quick-view](https://yourprojects.quarkino.io/api/modular/v1/content-post-quick-view)

**Permission:** Admin

**Method:** GET

**Description:** Displays the information of each post

[Postman Link](https://google.com/)

### **Post Relations Search**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-relations-search](https://yourprojects.quarkino.io/api/modular/v1/content-post-relations-search)

**Permission:** Admin

**Method:** GET

**Description:** search in posts for adding to relations post

[Postman Link](https://google.com/)

### **Post Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-save](https://yourprojects.quarkino.io/api/modular/v1/content-post-save)

**Permission:** Admin

**Method:** POST

**Description:** Save a post in the admin panel

[Postman Link](https://google.com/)

### **Postun Pin**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-post-unpin](https://yourprojects.quarkino.io/api/modular/v1/content-post-unpin)

**Permission:** Admin

**Method:** POST

**Description:** Content post unpin

[Postman Link](https://google.com/)

### **Posts Mass Destroy**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-posts-mass-destroy](https://yourprojects.quarkino.io/api/modular/v1/content-posts-mass-destroy)

**Permission:** Admin

**Method:** DELETE

**Description:** Destroy a Number of Posts (Hard Delete)

[Postman Link](https://google.com/)

### **Posts Mass Restore**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-posts-mass-restore](https://yourprojects.quarkino.io/api/modular/v1/content-posts-mass-restore)

**Permission:** Admin

**Method:** PUT

**Description:** Undelete a Number of Posts

[Postman Link](https://google.com/)

### **Posts Mass Trash**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-posts-mass-trash](https://yourprojects.quarkino.io/api/modular/v1/content-posts-mass-trash)

**Permission:** Admin

**Method:** DELETE

**Description:** Delete a Number of Posts (Soft Delete)

[Postman Link](https://google.com/)

### **Slug Suggest**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-slug-suggest](https://yourprojects.quarkino.io/api/modular/v1/content-slug-suggest)

**Permission:** Admin

**Method:** POST

**Description:** Review duplicate slugs and suggest unique slugs if duplicate

[Postman Link](https://google.com/)

### **Faq Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-fetch)

**Permission:** Admin

**Method:** GET

**Description:** Fetch a Faq of a organization

[Postman Link](https://google.com/)

### **Faq Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-grid](https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-grid)

**Permission:** Admin

**Method:** GET

**Description:** View a grid for Organizations FAQs

[Postman Link](https://google.com/)

### **Faq Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-save](https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-save)

**Permission:** Admin

**Method:** POST

**Description:** Save an Faq Post

[Postman Link](https://google.com/)

### **Faq Save Order**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-save-order](https://yourprojects.quarkino.io/api/modular/v1/content-themes-faq-save-order)

**Permission:** Admin

**Method:** POST

**Description:** Save the orders of a FAQ manage

[Postman Link](https://google.com/)

### **Slideshows Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-slideshows-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-themes-slideshows-fetch)

**Permission:** Admin

**Method:** GET

**Description:** get list of slideshows

[Postman Link](https://google.com/)

### **Slideshows Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-themes-slideshows-save](https://yourprojects.quarkino.io/api/modular/v1/content-themes-slideshows-save)

**Permission:** Admin

**Method:** POST

**Description:** save slideshows

[Postman Link](https://google.com/)

### **Type Config Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-config-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-type-config-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch content type config

[Postman Link](https://google.com/)

### **Type Config Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-config-save](https://yourprojects.quarkino.io/api/modular/v1/content-type-config-save)

**Permission:** Admin

**Method:** POST

**Description:** save content type configs

[Postman Link](https://google.com/)

### **Type Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-type-fetch)

**Permission:** Administrator

**Method:** GET

**Description:** Content type fetch

[Postman Link](https://google.com/)

### **Type Grid**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-grid](https://yourprojects.quarkino.io/api/modular/v1/content-type-grid)

**Permission:** Administrator

**Method:** GET

**Description:** Type Grid

[Postman Link](https://google.com/)

### **Type Regenerate Versions Fetch**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-regenerate-versions-fetch](https://yourprojects.quarkino.io/api/modular/v1/content-type-regenerate-versions-fetch)

**Permission:** Admin

**Method:** GET

**Description:** fetch regenerate images versions modal

[Postman Link](https://google.com/)

### **Type Regenerate Versions Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-regenerate-versions-save](https://yourprojects.quarkino.io/api/modular/v1/content-type-regenerate-versions-save)

**Permission:** Admin

**Method:** POST

**Description:** dave the artisan command on ArtisanCommandQueue

[Postman Link](https://google.com/)

### **Type Save**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-type-save](https://yourprojects.quarkino.io/api/modular/v1/content-type-save)

**Permission:** Administrator

**Method:** POST

**Description:** Content type upstream save

[Postman Link](https://google.com/)

### **Type List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/content-types-list](https://yourprojects.quarkino.io/api/modular/v1/content-types-list)

**Permission:** Admin

**Method:** GET

**Description:** Get the list of content types.

[Postman Link](https://google.com/)
