# minip
A knowledge based Decision Support System to suggest career paths in the field of Computer Engineering.

In today’s education environment, where it is very hard to choose your career option in a right way. Currently there is an increasing interest in Machine learning and its role in educational systems, making this as a new growing research area. Machine learning practices can provide signiﬁcant contribution by providing support to users for opting the right education domain to shape their career. In this paper, we have proposed education decision support system model, which compromises the components i.e. user interface, inference engine and knowledge base. Our model supports active machine learning type techniques to provide a knowledge discovery pattern, thus it also includes the knowledge of several domain experts. Our proposed model generates the output results (career choice) by taking several past studies, records, student’s information and current education environment into consideration with the help of respective domain experts. Further, we have evaluated the performance of our model by considering several test cases.

Proposed System Overview

The proposed system consists of a database and a python program. In order to provide a right advice to the students we have proposed a model i.e. Career Advice Model (CAM) which is based or machine learning techniques and used a rule based decision support system to generate the expert knowledge
1. User Interface: This is the ﬁrst component of CAM through this user interact with the system. This consist of two modules one for user’s personal skills and information processing and second for the personality analysis.
2. Inference Engine: This is the information processing component of CAM and having rule based decision support capability.
3. Knowledge base: This is the core component of CAM which consists of several knowledge sources for supporting the inference engine so that new knowledge is discovered from the previous knowledge patterns.

Challenges

1	Retrieval of the data 
2	Updating the data in the database.
3	Providing an efficient Training Set
4	Optimizing and Calculating the results
5	Integrating all the features in Software
6	Integrating into a Software


 Software Requirements
 
•	A supported version of Microsoft Windows
•	Python ( programming language) – version 2.7 and Higher
•	Orange.biolab.si
•	Oracle database system

 
Low Level Design
	Module 1: User Interface Module
1.	Form Generation
2.	Get Inputs
3.	Inputs to Software required Format
	Module 2: Interface Engine
1.	Visual Programming using ‘Orange’
2.	Formatting Data using ‘Python’
	Module 3: Result Generation
1.	Domain Expert Knowledge
2.	Training Set Generation
3.	Descriptive Data Mining using ‘Naïve-Bayesian Classification’
4.	Calculating Probabilities
5.	Illustrating Career Choices and Courses, Career Paths 
