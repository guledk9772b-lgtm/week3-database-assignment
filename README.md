# SQL Student Table Assignment

## Description

This assignment demonstrates basic SQL operations for creating and managing a `student` table.

The SQL queries cover:

* Creating a table
* Inserting student records
* Updating student information

## Question 1: Create the Student Table

The `student` table contains three columns:

* `id` – An integer and the primary key
* `fullName` – A text field that can contain up to 100 characters
* `age` – An integer representing the student's age

```sql
CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName VARCHAR(100),
    age INT
);
```

## Question 2: Insert Student Records

Three student records are inserted into the table.

```sql
INSERT INTO student (id, fullName, age)
VALUES
(1, 'Ahmed Ali', 19),
(2, 'Mohamed Hassan', 18),
(3, 'Abdi Noor', 21);
```

## Question 3: Update Student Age

The age of the student with ID `2` is updated from `18` to `20`.

```sql
UPDATE student
SET age = 20
WHERE id = 2;
```

## Final Result

After running all the queries, the student table contains:

| ID | Full Name      | Age |
| -: | -------------- | --: |
|  1 | Ahmed Ali      |  19 |
|  2 | Mohamed Hassan |  20 |
|  3 | Abdi Noor      |  21 |

## Skills Practiced

* `CREATE TABLE`
* `INSERT INTO`
* `UPDATE`
* Primary keys
* SQL data types
* Basic database management

## Conclusion

This assignment demonstrates how to create a database table, add records, and modify existing data using basic SQL statements.
