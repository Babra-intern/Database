# Question 1 
`SELECT sc.name, cs.class_name
FROM enrollments e
JOIN students sc ON e.student_id = sc.id
JOIN classes cs ON e.class_id = cs.id;
`

# Question 2 

`
SELECT s.name AS student_name, c.class_name
FROM students AS s
LEFT JOIN enrollments AS e ON s.id = e.student_id
LEFT JOIN classes AS c ON e.class_id = c.id;

`

# Question 3 

`
SELECT sc.name
FROM enrollments e
Join students sc on e.student_id = sc.id 
Join classes cs on  e.student_id = cs.id 
Group by cs.class_name , sc.name 
`


# Question 4 
`
SELECT s.name , cs.teacher
FROM enrollments e
Join students s on e.student_id = s.id
Join classes cs on e.class_id = cs.id
`