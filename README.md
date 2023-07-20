# DBMS
The university data is loaded into the database using the PostgreSQL server. Following that, SQL Triggers, Recursive Queries, and Scalar Functions were implemented to enforce rules and successfully maintain data integrity.

**Exercise 1**:  SQL Query which takes the name of a table and row count k as input from the user, and then returns the table with appropriate names as column headings and any k rows of the table.

**Exercise 2**:  SQL Query which takes course_id as input from a user and then returns all the prerequisites of the given course with its title and course_id. <br>
[Note: Return not only the direct prerequisites of the course, but also prerequisites of prerequisites, and so on.]

**Exercise 3**:  Create a trigger to enforce the constraint: “An instructor cannot teach two different sections in a semester in the same slot”. <br>
[Note: The constraint can be violated by changes to the teaches relation as well as the section relation.]

**Exercise 4**:  SQL Query which takes the roll number of a student as input from a user and returns the CGPA of the student.

**Exercise 5**: <br>
Return the top-k students for the following three cases: [Use the ranking() function on CGPA] : <br>
   a) Top-k students with highest CGPA. <br>
   b) Top-k students with highest CGPA in a given department. <br>
   c) Top-k students with highest CGPA enrolled in a given course (need to consider all the students who have taken the course across all the offerings of the course).
