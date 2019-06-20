# Secure-Count-Query-on-Encrypted-Biomedical-Data
We designed a secure framework for outsourcing genomic data and executing count query on it. Count query determines the number of records in the database that match a query predicate and it is very useful for genetic association studies to compute several statistical algorithms.

Count query is a simple and straightforward operation if the data is stored in plaintext and traditional database management systems (DBMS) support a built-in operation for it. However, these DBMSs are not designed to execute count query operation on the encrypted data.

We used a tree-based indexing algorithm to pre-filter the search result. Execution of a query is done by traversing an encrypted tree where the decision of traversing each node is made by checking whether a query predicate matches with a particular branch of the tree.

Technologies: Java, MySQL

Project Owners: Zahidul Hasan, Safiur Mahdi, Noman Mohammed
