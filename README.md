Download Link :https://programming.engineering/product/csc4710-6710-assignment-1/


# CSc4710-6710-Assignment-1
CSc4710/6710 Assignment 1
Problem 1 (100 points)

Consider the following relational schema (the primary keys are underlined):

department(dName, location)

course(cID, clevel, cName, prerequisite, duration, credits)

offers(dName, cID)

instructor(instID, instName, office)

works_for(instID, dName)

teaches(instID, cID)

student(sID, sName, dob)

enrolled(sID, cID)

For (1) to (8) provide the following queries: (a) Relational Algebra; (b) Domain Relational Calculus; and

SQL. For (9) and (10) provide only SQL queries.

Which courses are of 3 credits?

Which courses are offered by the department of computer science?

Which departments offer courses with ‘3’ credits but not ‘4’ credits?

Which department has the highest number of enrolled students?

Which instructor teaches the highest number of credits?

Which courses belong to more than one department?

Which students are taking courses from both “Computer science” and “Mathematics” departments?

Which courses are provided at both undergraduate (clevel = 4XXX) and graduate (clevel = 6XXX) levels?

For each department and course, give the number of courses provided at each level (1xxx,2xxx,3xxx,4xxx,6xxx). Display the results in ascending order of department name, and within each department, in ascending order of course levels (clevel).

For each group of students, in a department, give the average number of students, minimum number of students, maximum number of students. Display the results in descending on average number of students.
