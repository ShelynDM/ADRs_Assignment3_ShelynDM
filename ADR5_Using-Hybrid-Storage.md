Choosing the best data storage solution for the social networking mobile app for the university depends on various factors, including scalability, performance, data structure, and development complexity. Here are some options to consider:

Relational Database Management System (RDBMS):

Examples: MySQL, PostgreSQL, SQL Server
Description: RDBMSs are traditional databases that store data in structured tables with rows and columns. They are suitable for applications with well-defined data structures and complex relationships between entities (e.g., users, posts, comments).
Benefits: ACID compliance, strong consistency, support for complex queries and transactions.
Considerations: May require schema migrations, less flexible for schema changes, may have limitations in scaling horizontally.
NoSQL Databases:

Examples: MongoDB, Cassandra, Couchbase
Description: NoSQL databases are designed for storing and retrieving unstructured or semi-structured data. They offer flexibility in data modeling and scalability for handling large volumes of data.
Benefits: Schema flexibility, scalability (especially horizontally), better performance for certain use cases like real-time analytics or high-volume data ingestion.
Considerations: Eventual consistency, lack of ACID transactions (in some cases), may require denormalization for complex queries.
Hybrid Approaches:

Examples: Using a combination of RDBMS and NoSQL databases (e.g., PostgreSQL for structured data and Elasticsearch for full-text search).
Description: Combining different data storage solutions to leverage their respective strengths for different parts of the application.
Benefits: Flexibility in choosing the right tool for the job, optimal performance and scalability for different data types and access patterns.
Considerations: Increased complexity in managing multiple data stores, potential data consistency challenges.

For a social networking mobile app for a university, a combination of relational and NoSQL databases may be suitable, depending on the data structure and access patterns. For example, you might use an RDBMS for user authentication and structured data (e.g., user profiles, courses), while leveraging a NoSQL database for flexible data modeling (e.g., user-generated content, activity feeds). Additionally, cloud-based solutions can offer scalability and ease of management, especially for applications with unpredictable traffic patterns.

# ADR4: Application Permissions

Date: February 11, 2024

**Status**

**Context**

**Decision**

**Consequence**
