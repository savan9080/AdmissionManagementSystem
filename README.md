# AdmissionManagementSystem
This project conains a jupyter-notebook file which uses the numpy and pandas to generate random student data, college data and give them admission to their preferred branch from selected college after giving them a rank based on the marks.

## How to use?
If you have student details like marks of different subject and enrollment no.or serial no. Then you can just comment the code which generates all the random records for students and save all this data to `studentdetails.csv`. Same for college details `College_details.csv`.
It will generate 200 student data on each day and store the remaining seats of each college in `Remaining_Seats.csv` and this details is used to give admission on next day.
One can also use round based system instead of day.(i.e. Round 1,Round 2...)
After end of all round or day it will store the details of students who haven't got admission in any college in the file `Not_Admitted_Students.csv` and generates file `Admission_Details_All_Students.csv` which contains the details of student with their branch and college in which they got admission.
The file `Final_Remaining_Seats.csv` has the no. of vacant seats of all colleges after whole admission process is over.

## Conclusion:
This is just a basic working of the ACPC(Admission Committee for Professional Courses) which works as the Admission Commission in Gujarat for Engineering after 12th Science and Diploma Engineering (D2D-Diploma to Degree).  
