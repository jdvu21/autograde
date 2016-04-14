# autograde
At The University of C the CSI class is taught using the one-true programming language, C. Students are working on their first programming assignment (a very exciting one involving the square feet of a house given the width and depth!). You are the TA (Teaching Assistant) for the course. The instructor has told you grade the programs.

In order to grade the programs, you will need to compile and build them, run them with some test data recording the results, and give the student some feedback on programming style (or lack thereof). To do all of this manually would take a long time since there are 2 classes of 45 students apiece. However, by using your recently-honed UNIX bash skills you know you could automate much of this, at least to the point where it is much easier to grade.

Create a script, autograde, that will create a report for each student in the class that contains enough feedback so that you, as a TA, can quickly score the student’s result. The report must include (not at all in this order):

Student’s full name
Student’s username
The step used to build the program (compile and link), and any errors the compiler produces during these stages
The source code of the program, with syntax highlighting of course
Running the program with 3 different test cases. The interaction with the program should be exactly the same as if you manually interacted with their program, e.g.,
        
Enter the width of the house (in feet):  25  
Enter the depth of the house (in feet):  30  
The house is 750 square feet

      
Note: The code for the above program is at ~collard/UniversityofC/CSI/jdoe/house.c on the UNIX server

The output is two columns, side by side. You will want to use enscript, and all its features
The output is in PDF
Each student will have a separate PDF file, with their username as the filename, e.g.., jdoe.pdf, stored in a single directory (of your own)
Your work for this must be in a GitHub repository. You can make one of your own, or ask me for one to use. The repository must be private, and include myself as a collaborator (otherwise, I would not see it). My github username is mlcollard. Make sure to commit as you are working, not just at the end.

The program is due Wednesday, April 13
