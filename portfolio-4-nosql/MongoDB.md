## Mongo DB

MongoDB was chosen as the NOSQL database to be used for this portfolio because it allows related data to be stored together in a document, instead of in multiple tables​‌.

In this case, each student record contains all student information and an embedded array, thereby providing faster retrieval of complete records for a student. This model is suitable for academic records as it supports flexible schemas, reduces complex joins and allows for easy retrieval


##

The chosen query was run to retrieve the document of a student using a student identifier. It returned the student's records and the embedded subjects result. This demonstrates how MongoDB stores data