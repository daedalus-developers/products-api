## Products API

### Prerequisites:
* Java 21
* Docker

### Minimum Functional Requirements:
1. The REST API should serve the following routes:

| METHOD | ENDPOINT           | DESCRIPTION |
| ------ |--------------------| ----------- |
| GET | ```/api/products```     | Retrieve all products in the database |
| POST | ```/api/products```     | Create new product in the database |
| GET | ```/api/products/{id}``` | Retrieve a product in the database |
| PUT |```/api/products/{id}``` | Update a product in the database |
| DELETE | ```/api/products/{id}``` | Delete a product in the database |

2. The REST API should accept and serve data in JSON format
3. The Product entity must have the following properties:
```product_id```, ```name```, ```description```, ```price```, ```quantity``` 

