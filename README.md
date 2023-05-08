Download Link: https://assignmentchef.com/product/solved-student-database-solved
<br>
1. Specification This programming project involves writing a program to manage a student database. The interface to the program should be a Swing based GUI that looks similar to the following:

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/203.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/203.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>A combo box should allow the user to select one of the four database actions shown. The database should be implemented as a HashMap, with the Id field as the key and a Student record as the value. The selected operation should be performed when the user clicks the Process Request button. If the user attempts to insert a key that is already in the database an error message should be displayed using a JOptionPane message dialog box. If the user attempts to delete, find or update a record that is not in the database, a message should also be displayed in a JOptionPane. After each successful operation is completed a JOptionPane window should be displayed confirming the success. In the case of a successful Find request, a window should pop up containing the student’s Id, name, major and current GPA. When the user selects the Update request, the following JOptionPane windows should be displayed to gather information about a course that has just been completed. As a result, the Student record in the database will be updated accordingly. User input values should be checked and a warning message should be displayed in a JOptionPane for inappropriate values (such as empty textfields for Id, name or major).




<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/885.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/885.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>When the main application window is closed, the student records from the database will be written into the text file outData.txt, each student data (including his/her GPA) on a separate line. The last line of the file will contain the total number of student records in the database and their average GPA value.

The program should consist of two classes.

1. The first class P4GUI should define the GUI and handle the database interactions. It should be hand-coded and not generated by a GUI generator. 2

2. The second class named Student, should define the student record. The class defines the instance variables id, name, major, totalCredits (as total number of credits completed) and totalQP (as total quality points). The quality points for a course is calculated as the numeric value of the grade received in the course (A = 4; B = 3; C = 2; D = 1; F = 0) times the number of credit hours for that course. The values of totalCredits and totalQP will be used to calculate the GPA by dividing totalQP by totalCredits. The class Student should have the following three methods: a. A constructor with arguments that is used when new student records are created It takes Id, name and major as parameters and will initialize totalCredits and totalQP to zero; b. A method courseCompleted that should accept the course grade and credit numbers and will update the variables used to compute the GPA. It will be called when an Update request is made. c. A method overriding toString that returns a labeled string containing the student id, name, major and GPA.

Finally, when a student has not yet completed any course, the GPA should be displayed as 4.0.

Your program should compile without errors.

The Google recommended Java style guide (https://google.github.io/styleguide/javaguide.html) should be used to format and document your code.

Specifically, the following style guide attributes should be addressed:

 Header comments include filename, author, date and brief purpose of the program.

 In-line comments used to describe major functionality of the code.

 Meaningful variable names and prompts applied.

 Class names are written in UpperCamelCase.

 Variable names are written in lowerCamelCase.

 Constant names are in written in All Capitals.

 Braces use K&amp;R style.

In addition the following design constraints should be followed:

 Declare all instance variables private

 Avoid the duplication of code

Test cases should be supplied in the form of a table with columns indicating what aspect is tested, the input values, expected output, actual output and if the test case passed or failed. This table should contain 5 columns with appropriate labels and a row for each test case. Note that the actual output should be the actual results you receive when running your program and applying the input for the test record. Be sure to select enough different kinds of employees and situations to completely test the program.

Submission Requirements

Submit the following to the Project 2 assignment area no later than the due date listed in your LEO classroom.

1. The source files P4GUI.java and Student.java and the program generated output file outData.txt. The source code should use Java code conventions and appropriate code layout (white space management and indents) and comments. All submitted files may be included in a .zip file.

2. The solution description document P4SolutionDescription (.pdf or .doc / .docx) containing the following:

(1) Assumptions, main design decisions, error handling;

(2) Test cases table

(3) Screen captures showing successful program compilation and test cases execution. Each screen capture should be properly labeled, clearly indicated what the screen capture represents.

(4) Lessons learned from the project;