# mosu333-week3-sql-assignment

## Question 1: Create the student table

CREATE TABLE student (
  id INT PRIMARY KEY,
  fullName VARCHAR(100),
  age INT
);

## Question 2: Insert at least 3 records

INSERT INTO student (id, fullName, age)
VALUES
  (1, 'John Mwangi', 22),
  (2, 'Amina Hassan', 19),
  (3, 'David Otieno', 25);

## Question 3: Update age of student with ID 2

UPDATE student
SET age = 20
WHERE id = 2;
