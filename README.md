# MySQL
In this Repositorie you will find 10 basic and 10 advanced querys about a faculty database.

![Alt text](database.PNG)

- Description of the basic querys. You will find the solution in ENTREGA_SENT_BASICAS.sql-

1- Obtain a list that shows the identifier of the teachers, their name andsurnames, as well as the code of the subjects taught and their name.

2- Obtain the name of each professor together with the ID of their thesis supervisor. In case ofnot having a thesis supervisor in the list should appear "Does not have"

3- Name and surname of pairs of teachers whose difference in seniority (in valueabsolute) is less than two years and belong to the same department. Show theage of each of them in    years. Use the MONTHS_BETWEEN function

4- Trios of subjects belonging to the same subject. The name ofthe 3 subjects followed by the code of the subject to which they belong.

5- Name and surname of all the students who are taught by Enrique Soler. Have inNote that the ASINGNATURE, GROUP and COURSE attributes of the tables must be usedTEACH and ENROLL.    Each student must appear only once. Sort them bysurname name.

6- List with the name of the subjects, name of the subject to which it belongs andName, surname and credit load of the teachers who teach it. The listing mustbe ordered by subject    code and in reverse alphabetical order of the name ofsubject

7- List with the name of the subject, name of the department to which it is assigned,total credits and percentage of practical credits, ordered decreasingly by thepercentage of      practical credits. Those subjects whose total number of credits,Practical or theoretical not specified should not appear in the list.

8- Surnames containing the letter elle ('ll') of both students and teachers.

9- Show the name and surname of each professor along with those of his thesis supervisor andthe number of director investigation tranches. Remember that the thesis supervisor ofa    teacher is given by the attribute DIRECTOR_THESIS and the number of sections isfound in the INVESTIGATORS table. The names of each teacher and their directormust appear in the    following format: 'The Director of Angel Mora Bonilla is ManuelEnciso Garcia-Oliveros'.

10-List the names of all students in alphabetical order. If said studenthad another student enrolled exactly at the same time as him, show thename of this second student next to      him

-Description of the advanced querys. You will find the solution in SENTENCIAS_ADVANCED.sql-


1- Show the code of the subjects taught by Professor Manuel Enciso, using asubquery.

2- Show the code of the students who receive class from the teacher code C-34-TU-00,using a subquery

3- Calculate the number of credits assigned to each department. Thecredits established for each subject of the department, not if they teach it or notteachers of the same, that    is, directly add the credits of the subjects andgather subjects and departments directly, without using any other tables

4- For each office number, indicate the total credits taught by professorslocated in them

5- View the subject with the highest number of credits in which each has enrolledstudent.

6- View for each department, the subject with the least credits

7- View the department with the greatest number of subjects under its charge

8- List the professors who have a higher than average credit load. Use clauseHAVING and nest grouping functions

9- List the name of the departments that do not have any subject with more than 6credits.

10- Show the pairs of teachers who have no student in common.
