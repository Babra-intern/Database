# Question 1 
`SELECT sc.name, cs.class_name
FROM enrollments e
JOIN students sc ON e.student_id = sc.id
JOIN classes cs ON e.class_id = cs.id;
`

# Question 2 

`select sc.name 
from enrollments as e
Join students sc ON e.student_id = sc.id
`

# Question 3 

`
select sc.name
from enrollments e
Join students sc on e.student_id = sc.id 
Join classes cs on  e.student_id = cs.id 
Group by cs.class_name , sc.name 
`


# Question 4 
`
select s.name , cs.teacher
from enrollments e
Join students s on e.student_id = s.id
Join classes cs on e.class_id = cs.id
`