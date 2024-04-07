---
sidebar_position: 3
---

# Core Concepts
Quarkino is designed to empower developers with a flexible, feature-rich platform that simplifies the creation of diverse web applications. At the heart of Quarkino's power are its APIs, settings, and modular capabilities, which together provide a robust foundation for developers.

## API Overview

Quarkino offers a vast suite of over 300 APIs, with more than 100 APIs readily accessible for client-side development. These APIs are crafted to support a wide array of functionalities, from information storage and retrieval to content listing and modification, all responding in a consistent JSON data format.

## Response Codes

Understanding the response codes is crucial for effective error handling and debugging:

- 200: Success - The request was successful.
- 400: Bad Request - The request could not be understood by the server.
- 403: Forbidden - The request was valid, but the server is refusing action.
- 404: Not Found - The requested resource could not be found.
- 422: Not Found - The requested resource could not be found. // TODO
- 429: Not Found - The requested resource could not be found. // TODO
- 500: Internal Server Error - The server encountered an unexpected condition.

## API Structure

The structure of Quarkino’s API incorporates the project domain address, versioning, and a modular prefix, ensuring organized and scalable API endpoints. For example, calling an endpoint might follow a structure like: https://yourproject.quarkino.io/api/v1/modular/endpoint.

## API Methods

Quarkino supports the four fundamental HTTP methods for RESTful services: GET, POST, PUT, and DELETE, allowing for a comprehensive range of actions from creating and reading to updating and deleting resources.

## API Categories

- Management Panel Endpoints: Reserved for admin-level access, these endpoints are used for backend management functionalities. // TODO: admins roles administrator
- User Endpoints: Designed for ordinary users to interact with their content within the permissions granted to their user role.
- Guest Endpoints: Accessible without authentication, suitable for operations that do not require user identification.

For endpoints requiring authentication, the user token obtained during the login process must be included in the request header.

### Using `curl`

```bash
curl 'https://yourproject.quarkino.io/api/modular/v1/cart-my-orders-list' \
  -H 'Accept: application/json' \
  -H 'Accept-Language: en-US,en;q=0.5' \
  -H 'locale: en' \
  -H 'Authorization: Bearer YOUR_USER_TOKEN'
```

Make sure to replace YOUR_USER_TOKEN with the actual user token you've received during authentication.

### Using `axios` in JavaScript

```jsx
const axios = require('axios');

axios.get('https://yourproject.quarkino.io/api/modular/v1/cart-my-orders-list', {
    headers: {
        'Accept': 'application/json',
        'Accept-Language': 'en-US,en;q=0.5',
        'locale': 'en',
        'Authorization': 'Bearer YOUR_USER_TOKEN'
    }
})
.then(response => {
    console.log(response.data);
})
.catch(error => {
    console.error('Error:', error);
});
```

## Multilingual Support

Quarkino is a multilingual platform capable of managing and delivering content in multiple languages. Content can be requested in specific languages by including the desired language key in the request header, thereby tailoring the user experience to diverse global audiences.

```bash
curl 'https://yourproject.quarkino.io/api/modular/v1/content-post-lists?type=products&including[]=title&including[]=image&including[]=synopsis&including[]=available_wares_count&including[]=ware_sale_price&including[]=ware_original_price&locale=fa&paginated=1&page=1&sort=published_at' \
  -H 'Accept: application/json' \
  -H 'Accept-Language: en-US,en;q=0.5' \
  -H 'Referer: https://yourproject.com/en/products' \
  -H 'locale: en'
```

```jsx
const axios = require('axios');

axios.get('https://yourproject.quarkino.io/api/modular/v1/content-post-lists', {
    params: {
        type: 'products',
        including: [
            'title',
            'image',
            'synopsis',
            'available_wares_count',
            'ware_sale_price',
            'ware_original_price'
        ],
        locale: 'en',
        paginated: 1,
        page: 1,
        sort: 'published_at'
    },
    headers: {
        'Accept': 'application/json',
        'Accept-Language': 'en-US,en;q=0.5',
        'Referer': 'https://yourproject.com/en/products',
        'locale': 'en'
    }
})
.then(response => {
    console.log(response.data);
})
.catch(error => {
    console.error('Error fetching the content post list:', error);
});

```

## Efficient Data Handling

Endpoints designed to list or detail entities offer the flexibility to including or excluding specific resources in the output. This feature, available in GET type APIs, optimizes bandwidth usage and enhances response times by allowing developers to specify exactly what data should be returned.

### Using `curl`

Including Specific Fields
To include only specific fields in the response, such as title, image, and price:

```bash
curl 'https://yourproject.quarkino.io/api/modular/v1/content-post-lists?including[]=title&including[]=image&including[]=price' \
  -H 'Accept: application/json' \
  -H 'locale: en'
```

Excluding Specific Fields
To exclude specific fields from the response, such as description and details:

```bash
curl 'https://yourproject.quarkino.io/api/modular/v1/content-post-lists?excluding[]=description&excluding[]=details' \
  -H 'Accept: application/json' \
  -H 'locale: en'
```

### Using `axios` in JavaScript

Including Specific Fields
To specify fields to include in the axios request:

```jsx
const axios = require('axios');

axios.get('https://yourproject.quarkino.io/api/modular/v1/content-post-lists', {
    params: {
        including: ['title', 'image', 'price']
    },
    headers: {
        'Accept': 'application/json',
        'locale': 'en'
    }
})
.then(response => {
    console.log(response.data);
})
.catch(error => {
    console.error('Error:', error);
});
```

Excluding Specific Fields
To specify fields to exclude in the axios request:

```jsx
const axios = require('axios');

axios.get('https://yourproject.quarkino.io/api/modular/v1/content-post-lists', {
    params: {
        excluding: ['description', 'details']
    },
    headers: {
        'Accept': 'application/json',
        'locale': 'en'
    }
})
.then(response => {
    console.log(response.data);
})
.catch(error => {
    console.error('Error:', error);
});
```

## Feature-Based Architecture

Quarkino's architecture is centered around features, enabling you to activate and use any feature according to your project needs. This approach ensures that developers have access to a comprehensive set of functionalities, such as:

- Content Management
- User and Role Management
- E-commerce Solutions
- Payment Gateways
- Discount Coupons
- Shipping Methods
- And many more, all configurable and manageable through Quarkino's intuitive dashboard.

## API Usage Examples

Explore how to interact with Quarkino's APIs efficiently through practical examples. This section provides insights into making API calls, including handling authentication, selecting specific data fields, and working within the multilingual capabilities of the platform. These examples cover common use cases, enabling you to quickly integrate Quarkino's functionalities into your projects.

### Fetching Content Post Lists

Retrieve a list of content posts, specifying only the fields you need to optimize data transfer and processing speed.

Using `curl`

```bash

curl 'https://yourproject.quarkino.io/api/modular/v1/content-post-lists?type=products&including[]=title&including[]=image&locale=fa&paginated=1&page=1&sort=published_at' \
  -H 'Accept: application/json' \
  -H 'Authorization: Bearer YOUR_USER_TOKEN'
```

Using `axios`

```jsx
axios.get('https://yourproject.quarkino.io/api/modular/v1/content-post-lists', {
  params: {
    type: 'products',
    including: ['title', 'image'],
    locale: 'en',
    paginated: 1,
    page: 1,
    sort: 'published_at'
  },
  headers: {
    'Accept': 'application/json',
    'Authorization': 'Bearer YOUR_USER_TOKEN'
  }
})
.then(response => console.log(response.data))
.catch(error => console.error('Error:', error));
```

### Fetching Settings

Access specific settings entries, such as site title and contact details, to display on your site.

Using `curl`

```bash
curl 'https://yourproject.quarkino.io/api/modular/v1/setting-get?entries[]=site_title&entries[]=contact_details' \
  -H 'Accept: application/json' \
  -H 'Authorization: Bearer YOUR_USER_TOKEN'
```

### Using `axios`

```jsx
const axios = require('axios');

axios.get('https://yourproject.quarkino.io/api/modular/v1/setting-get', {
  params: {
    entries: ['site_title', 'socials', 'contact_details']
  },
  headers: {
    'Accept': 'application/json',
    'Authorization': 'Bearer YOUR_USER_TOKEN'
  }
})
.then(response => {
  console.log("Fetched settings:", response.data);
  // Process the settings as needed
})
.catch(error => {
  console.error('Error fetching settings:', error);
  // Handle the error
});
```

### Fetching Menu Locations

Retrieve menus for specific locations, demonstrating the inclusion of multiple fields in the response.

Using `curl`

```bash
curl 'https://yourproject.quarkino.io/api/modular/v1/menu-maker-get-location-menus?slugs[]=main-header-fa&slugs[]=main-footer-fa&including[]=menus&including[]=slug' \
  -H 'Accept: application/json' \
  -H 'Authorization: Bearer YOUR_USER_TOKEN'
```

Using `axios`

```jsx
axios.get('https://yourproject.quarkino.io/api/modular/v1/menu-maker-get-location-menus', {
  params: {
    slugs: ['main-header-fa', 'main-footer-fa'],
    including: ['menus', 'slug']
  },
  headers: {
    'Accept': 'application/json',
    'Authorization': 'Bearer YOUR_USER_TOKEN'
  }
})
.then(response => console.log(response.data))
.catch(error => console.error('Error:', error));
```

### User Login

Authenticate users by logging them into the system and retrieving a token for subsequent API calls.

Using `curl`

```bash
curl -X POST 'https://yourproject.quarkino.io/api/modular/v1/persons-login' \
  -H 'Accept: application/json' \
  -H 'Content-Type: application/json;charset=utf-8' \
  --data-raw '{"username":"user@example.com","password":"yourpassword"}'
```

Using `axios`

```jsx
const axios = require('axios');

axios.post('https://yourproject.quarkino.io/api/modular/v1/persons-login', {
  username: "user@example.com",
  password: "yourpassword"
}, {
  headers: {
    'Accept': 'application/json',
    'Content-Type': 'application/json'
  }
})
.then(response => {
  console.log("Login successful. Token:", response.data.token);
  // Handle success, such as saving the token for future requests
})
.catch(error => {
  console.error('Login failed:', error);
  // Handle errors, such as displaying a message to the user
});
```
