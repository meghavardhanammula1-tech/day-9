# day-9
Benefits of SQL is easy to learn and use. It helps users store and retrieve data quickly. It can handle large amounts of data and is used in many industries. SQL is also supported by most database management systems.

Limitations of SQL

- SQL can be difficult when working with very large databases.
- Different database systems may have slightly different SQL syntax.
- It is not suitable for all types of data, especially unstructured data.

Applications of SQL

SQL is used in many areas such as:

- Banking systems
- Hospitals and healthcare
- E-commerce websites
- Educational institutions
- Social media applications
- Data analysis and reporting

SELECT Statement

The SELECT statement is used to retrieve data from a table.

Example:

SELECT * FROM Students;

This query displays all records from the Students table.

WHERE Clause

The WHERE clause is used to filter records based on a condition.

Example:

SELECT * FROM Students
WHERE Age = 19;

This query displays students whose age is 19.

ORDER BY Clause

The ORDER BY clause is used to sort records.

Example:

SELECT * FROM Students
ORDER BY Age DESC;

This query displays records in descending order of age.

GROUP BY Clause

The GROUP BY clause is used to group rows with the same values.

Example:

SELECT Age, COUNT(*)
FROM Students
GROUP BY Age;

HAVING Clause

The HAVING clause is used to filter grouped data.

Example:

SELECT Age, COUNT()
FROM Students
GROUP BY Age
HAVING COUNT() > 1;

Simple SQL Program

CREATE TABLE Students (
StudentID INT,
Name VARCHAR(50),
Age INT
);

INSERT INTO Students
VALUES (1, 'Sravanthi', 19);

SELECT * FROM Students;

Conclusion

In this assignment, I learned about SQL, its commands, components, benefits, limitations, and applications. SQL is an important language used for managing and retrieving data from relational databases. It is widely used in real-world applications and helps in efficient data management.
