[[!3.2 Databases]]

Fundamental Theories

|Theory/Model|Description|
|---|---|
|**ACID**|A set of rules (Atomicity, Consistency, Isolation, Durability) that ensures reliable processing of transactions in a database.|
|**Entity-Relationship Model**|A conceptual framework used to describe the data and relationships in a database, often represented through Entity-Relationship Diagrams (ERDs).|

Key People

- **E.F. Codd**: The inventor of the relational database model and SQL, known for his work on database normalization.

Key Procedures/Protocols

- **Transaction Processing**: A sequence of database operations treated as a single unit of work, ensuring data consistency and integrity.
- **Data Normalization**: Achieved through First Normal Form (1NF), Second Normal Form (2NF), and Third Normal Form (3NF) to organize data efficiently.

Key Investigations

- **Concurrency Control**: Techniques used to manage simultaneous access to data in a multi-user environment, including locking mechanisms and timestamping.

Facts to Memorize

- SQL commands: SELECT, INSERT, DELETE, DROP
- ACID properties: Atomicity, Consistency, Isolation, Durability
- Types of relationships in ERDs: One to one, One to many, Many to many
- Normalization forms: 1NF, 2NF, 3NF
- Common data formats: CSV, JSON, EDI

Reference Information

- Common SQL functions: COUNT(), AVG(), SUM(), MAX(), MIN()
- Types of database management systems (DBMS): MySQL, Oracle, Microsoft SQL Server, PostgreSQL
- Data capture methods: OMR, OCR, Sensors, Barcodes

Concept Comparisons

|Concept|Flat File Database|Relational Database|
|---|---|---|
|Structure|Single table storing all data|Multiple tables with relationships|
|Data Redundancy|High, as data is repeated across records|Low, as data is normalized and linked via keys|
|Maintenance|Difficult, changes require updates in multiple places|Easier, changes in one table reflect across linked data|
|Efficiency|Less efficient due to redundancy|More efficient due to structured relationships|

Problem-Solving Steps

To normalize a database:

1. Identify all the data and its relationships.
2. Ensure the table is in First Normal Form (1NF) by eliminating repeating groups and ensuring atomicity.
3. Move to Second Normal Form (2NF) by ensuring all non-key attributes are fully dependent on the primary key.
4. Achieve Third Normal Form (3NF) by removing transitive dependencies.