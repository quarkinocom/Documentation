---
sidebar_position: 11
---

# Relations
The Relations feature is a versatile tool designed to dynamically establish and manage relationships between various entities within a platform. This feature facilitates the creation of connections such as wishlists, followings, playlists, and more, enabling users to interact with content and profiles in a personalized manner. It supports a wide range of functionalities, from social interactions to content organization, enhancing user engagement and providing a more customized experience.

## List of Features

- **User Wishlist**: Allows users to add products or content to a personal wishlist for easy access and future reference.
- **Follow Users or Profiles**: Enables users to follow other user profiles or legal entities, facilitating a social connection and content discovery.
- **Playlist Management**: Users can add videos or content to personal playlists, organizing their favorite media in one place.
- **Dynamic Relationship Management**: Provides the backend capability to define and modify the types of relationships between entities, supporting a wide variety of interactions within the platform.

## Usability Keys

- **Personalization**: By enabling users to mark favorites, follow profiles, and manage playlists, the Relations module significantly enhances the personalized experience of the platform.
- **Engagement**: Encourages user interaction by facilitating easy access to preferred content and profiles, thereby increasing platform engagement.
- **Flexibility**: The ability to define and manage different types of relationships allows for a highly adaptable feature set that can be tailored to specific project requirements.
- **Integration**: Designed to work seamlessly with other modules, offering combined features that enrich the platform's functionality and user experience.

## **Guest Endpoints**

Access to them without any token.

### **Change**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/relations-change](https://yourprojects.quarkino.io/api/modular/v1/relations-change)

**Permission:** Guest

**Method:** POST

**Description:** This endpoint is designed to manage changes in relationships between various entities within the platform. Through a POST request, it allows for the modification of existing relationships or the establishment of new ones, such as linking users to groups, assigning roles to users, or associating content with categories. The request must include details of the entities involved and the nature of the relationship change. This functionality is crucial for maintaining the dynamic and interconnected data structure of the platform, enabling flexible and efficient data management. It supports various use cases, from user management and content organization to dynamic grouping and access control, facilitating a robust and versatile platform ecosystem.

[Postman Link](https://google.com/)

## **User Endpoints**

Access with user token.

### **Favourite Change**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/relations-favourite-change](https://yourprojects.quarkino.io/api/modular/v1/relations-favourite-change)

**Permission:** User

**Method:** POST

**Description:** The endpoint, referred to in the documentation as /api/v1/content-post-fave, enables the addition or removal of a specified post to or from the favorite lists of the online user. This action is determined by the "switch" parameter in the request body, which accepts a boolean value. The request is made with a "raw" JSON body containing the "id" of the post and the "switch" boolean value to indicate the desired action.

[Postman Link](https://google.com/)

### **Favourites List**

**API Address:** [https://yourprojects.quarkino.io/api/modular/v1/relations-favourites-list](https://yourprojects.quarkino.io/api/modular/v1/relations-favourites-list)

**Permission:** User

**Method:** GET

**Description:** The endpoint allows users to retrieve a list of their favorite models. Accessed through a GET request, this service provides a straightforward way for users to view their personalized favorites list, contributing to a customized user experience within the platform. By delivering user-specific favorites, it enhances the relevance and engagement of the content or features available to each user. On success, the endpoint returns a detailed list of favorites, ensuring users have easy access to their preferred models.

[Postman Link](https://google.com/)

## **Admin Endpoints**

Access with admin token.
