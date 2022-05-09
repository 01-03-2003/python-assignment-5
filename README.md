ng

At a fairly abstract level, super() provides the access to those methods of the super-class (parent class) which have been overridden in a sub-class (child class) that inherits from it. Consider the code example given below, here we have a class named Square and an another class named Cube which inherits the class Square.

class Square:
     def __init__(self, side):
         self.side = side
  
     def area(self):
         return self.side * self.side
  
class Cube(Square):
      def area(self):
         face_area = self.side * self.side
         return face_area * 6
  
     def volume(self):
         face_area = self.side * self.side
         return face_area * self.In programming, we may require some specific input data to be generated several numbers of times. Sometimes, it is not enough to only display the data on the console. The data to be displayed may be very large, and only a limited amount of data can be displayed on the console, and since the memory is volatile, it is impossible to recover the programmatically generated data again and again. However, if we need to do so, we may store it onto the local file system which is volatile and can be accessed every time. Here, comes the need of file handling in C.

File handling in C enables us to create, update, read, and delete the files stored on the local file system through our C program. The following operations can be performed on a file.

Creation of the new file
Opening an existing file
Reading from the file
Writing to the file
Deleting the file
Functions for file handling
There are many functions in the C library to open, read, write, search and close the file. A list of file functions are given below:

No.	Function	Description
1	fopen()	opens new or existing file
2	fprintf()	write data into the file
3	fscanf()	reads data from the file
4	fputc()	writes a character into the file
5	fgetc()	reads a character from file
6	fclose()	closes the file
7	fseek()	sets the file pointer to given position
8	fputw()	writes an integer to file
9	fgetw()	reads an integer from file
10	ftell()	returns current position.
Inheritance is the mechanism to achieve the re-usability of code as one class(child class) can derive the properties of another class(parent class). It also provides transitivity ie. if class C inherits from P then all the sub-classes of C would also inherit from P.
 

Multiple Inheritance 
When a class is derived from more than one base class it is called multiple Inheritance. The derived class inherits all the features of the base case.
 

Multiple Inheritance

 

Syntax:

Class Base1:
       Body of the class

Class Base2:
     Body of the class

Class Derived(Base1, Base2):
     Body of the class
.....position
The most commonly used statement of MySQL Select statement. MySQL SELECT statement used to fetch data/records from database table.
In the INSERT INTO statement of MySQL, you can insert single or multiple rows into the database table.
MySQL UPDATE statement, you can update the single row using the UPDATE & WHERE clause statement at a time.
The DELETE statement is used to remove/delete a specific row or multiple rows using the MySQL DELETE & WHERE clause.
Table Of Content
SELECT Statement MySQL
INSERT Statement MySQL
UPDATE Statement MySQL
DELETE Statement MySQL
SELECT Statemet
res

Ad Hoc Queries Support. Basically, when we are in the Database Design phase, we have no idea of what queries might be executed.
Indexing. One of the most important features for a Database is Indexing, which results in improvements. ...
Replication. ...
Schema-less Database. ...
Document Oriented. ...
Aggregation Pipeline. ...
GridFS. ...
Sharding. ...
High Performance. ...
