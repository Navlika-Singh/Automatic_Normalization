# Automation of Normalization of an RDBMS

Normalization of a Relational Database System is one of the fundamental concepts of Database Management Systems. It aims at creating a set of relational tables with minimum data redundancy that preserve consistency and facilitate correct insertion, deletion, and modification. However, manually identifying the normal state of a database and then iteratively performing normalization to convert it into third normal form or other highest state of normalization is a time consuming procedure. In this course project we aim to solve this problem by automation of normalization of an RDBMS. Our approach first distinctly identifies the normalzation form of a given database, and then convert it to a given normalization state. Further, our approach can uniquely identify the best set of functional dependencies, candidate keys, prime and non prime attributes and othe related technicalities of the database. The output is a combination of table(s) in given normal state.

Components
- normalization.py: This python file contains the main code required to identify the normalization state of the input database and convert it into the desired normalization state.
- utils.py: This python file contains components required to assist the main function.
