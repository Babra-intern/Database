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
where age = 14`


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
` update students
set grade = 90 
where name = 'Bob'
`

# Question 8 

`delete from students 
where name = 'Eve'`


# Question 9 
`select name 
from students 
where grade is null`


# Question 10 
`Select age, COUNT(*) AS student_count
from students
group by age
order by age;
`



# Question 11 
` select  distinct age
from students `


# Quesion 12

`
select name
from students 
where grade > 80
`


# Question 13 
`
select age , name
from students 
order by grade desc
`


`
select age , name
from students 
order by name asc
`