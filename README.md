# MongoDB_Research
#### What is MongoDB?

MongoDB is a document database. Classified as a NoSQL database program, mongoDB stores data in flexible, JSON-like documents, meaning fields can vary from document to document and data structure can be changed over time

### What are NoSQL databases? How do they differ from SQL?

NoSQL databases cater to semi-structured data types: key-value, wide column, document (tree), and graph. Non-SQL databases are designed to handle large volumes of unstructured or semi-structured data.

<img width="481" alt="image" src="https://user-images.githubusercontent.com/118978642/233040511-7aff5eac-781e-4840-9777-a8664cd44933.png">

### Why is MongoDB popular? What is it’s history?

MongoDB is popular for the following reasons:
- Schema-less data model: so easily scalable and adaptable. Good choice for storing unstructured or semi-structured data that may change over time.
- High performance and scalability: can handle millions of operations per second and supports sharding for horizontal scaling
- Developer-friendly, supports multiple programming languages and platforms
- Open-source and community-driven: it's free to use and modify and its large and active community also provides support, documentation, and third-party tools and plugins
- Compatible with most cloud platforms: so easy to deploy and manage in cloud-based environments
- Supports distributed database architectures: allows for seamless data management across multiple data centers and cloud providers

Short history of MongoDB:
- Developed in 2007 by Dwight Merriman, Eliot Horowitz, and Kevin Ryan.
- First released in 2009 as a backend storage solution for web apps.
- MongoDB Inc. was founded in 2010 for commercial support and development.
- Popular and widely used NoSQL database.
- Introduced document validation (2015) and Atlas cloud service (2016).
- Added multi-document ACID transactions in 2018.
- Over 100 million downloads and thousands of customers today.

### Diagram showing MongoDB architecture for storing data.

<img width="475" alt="image" src="https://user-images.githubusercontent.com/118978642/233044199-afbe8ab7-5b66-44a6-9874-ac61deaada0c.png">


### What is seeding in MongoDB? Why do Mongo databases need to be seeded?

Seeding is the process of adding initial data to a database when it's created or updated. It involves inserting predefined data into the database that is required for the application to function correctly. 

Seeding helps ensure that the database is correctly configured and populated with the data required for the application to function correctly. It can also save time and effort during testing and debugging phases and help ensure a smooth migration or update process.

### What port does MongoDB use?

The default port number for MongoDB for communication between client applications and the database server is: 27017. 

### How do you connect to a Mongo database?

Steps for connecting locally:
- install mongodb
- start mongodb ```mongodb```
usefule guide: https://zellwk.com/blog/local-mongodb/
