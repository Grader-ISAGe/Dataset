
                                  Arabic-Dataset

                        Questions/Student Answers with Grades
                           ==========================
                            
                                    
 

=====
a. Data Annotation

Our dataset consists of reported evaluations relate to answers submitted for three different exams submitted 
to three classes of students. The exams were conducted under natural conditions of evaluation. 
Each test consists of 16 short answer questions (a total of 48 questions). 
For each question, a model answer is proposed. 
Students submitted answers to these questions.  
The number of answers obtained is different from one question to another. 
The dataset includes a total of 2133 pairs (Model Answer, student answer). 
the Dataset encompasses 5 types of questions:
•	"عرف ": 		Define?
•	"إشرح":			Explain?
•	"ما النتائج المترتبة على": 	What consequences?
•	"علل": 			Justify?
•	"ما الفرق": 		What is the difference

 
For each pair, two grades (Mark1 and Mark2 ) are associated with a manual Average Gold Score
Both manual grades are available in the dataset.
Inter-Annotators Agreement:  - (Pearson Correlation: r=0.8384) 
			     - (Root Mean Square Error : RMSE=0.8381). 

For privacy reasons, no student identifiers are used in this Dataset.
=====
b. Folder Structure

 
	This folder contains 2 sub_folders for TXT and XML Versions
	The name of file is representative of its content. 
	We use the term "Mark" to specify "Grade"

     Sub-Folders :

	TXT-Version folder : 
		Files : (Model Answers List - 48).txt
			(Questions List - 48).txt
			(Student Answers List).txt
			(Number Of Answers  For Each Question For the 48 Questions).txt
			(Questions- Model Answers - Student Answers - Average Gold).txt
			(Questions- Model Answers - Student Answers - Grade1- Grade2-  Average Gold).txt
	XML-Version folder :                                            
		Files : (Type - Questions).xml
			(Questions-Model Answers).xml
			(Questions- Students Answers - Grade1 - Grade2 - Average Gold).xml
			(Questions- Students Answers - Average Gold).xml

	   

=======================
 
