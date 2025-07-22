# Question 1 

`SELECT * 
FROM students
`

# Question 2 
`
SELECT name, age
FROM students
`


# Question 3 
`
SELECT name
FROM students
WHERE age = 14`


# Question 4 
`
SELECT name
FROM students
order by grade asc
`

# Question 5 
`
SELECT name
FROM students
order by grade desc
LIMIT 2;
`

# Question 6 
`
INSERT INTO students(name, age, grade)
Values('Grace', 14, 90);
`

# Question 7 
` UPDATE students
SET grade = 90 
WHERE name = 'Bob'
`

# Question 8 

`DELETE FROM students 
WHERE name = 'Eve'`


# Question 9 
`SELECT name 
FROM students 
WHERE grade is null`


# Question 10 
`SELECT age, COUNT(*) AS student_count
FROM students
group by age
order by age;
`



# Question 11 
` SELECT  distinct age
FROM students `


# Quesion 12

`
SELECT name
FROM students 
oder by desc
limit 1
`


# Question 13 
`
SELECT age , name
FROM students 
order by grade desc

`


`
SELECT name, age
FROM students
ORDER BY grade DESC, name ASC;

`