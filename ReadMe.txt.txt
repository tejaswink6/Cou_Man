Assignment 1

================================== Part 1 (Courses) =================================================

-> .java file in src folder (Courses.java)

-> Sample input file - CoursesDetails.txt
   
 
================================ Part 2 (Contact List) =============================================
 
-> .java file in src folder (Acquaintances.java)

-> Sample input file - AcqDetails.txt


============================ Regarding Reading/Writing of data =======================================

-> User is asked if the input should be read from the file or if there is
   there is no file and the input will be given from the console.
	- The txt files should follow the fromat as given in the Sample text file (CoursesDetails.txt)
	  including the white spaces and new lines.

-> If there is a text file, data is read from the file.

-> If not, data is entered from the scratch by the user in the Console.

-> All the necessary operations are done on this data.

-> Data is written back to the text file every time the data is modified, but data is not read from the
 file everytime to ensure faster execution time. Data is read only at the start of the session.


=================================== Input Constrains ====================================================

-> Every date must be entered in the format YYYY-MM-DD.

-> Mobile No. should be a 10 digit numerical.

-> Email address should be a standard email address consisting of @ , . , com/in/au/...
   The last .com/.in/.. must be between 2 and 4 letters as in the case of actual email id's.

-> In Part-2(Contact List) the Date of last meeting should be after the Date of birth (for Relatives).

=========================================== -X- ==========================================================