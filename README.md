Download Link: https://assignmentchef.com/product/solved-sdev350-week2
<br>
In this lab, you will demonstrate you are comfortable navigating the AWS Oracle RDS environment and creating basic Schema objects using SQL developer or similar tool. This lab is a review of basic SQL.

<strong>You must connect to the AWS Educate Oracle RDS environment and complete these task to earn credit for this lab. </strong>

<strong>Lab Requirements </strong>

<ol>

 <li>Write and test a set of SQL statements that will drop the following tables:

  <ol>

   <li>Engineers</li>

   <li>Faculty</li>

   <li>Classes</li>

   <li>ClassEnrollments</li>

  </ol></li>

</ol>

Be sure to use the exact table names as listed.

Note: Since you probably have not yet created there tables, you will receive an error which is Okay and expected.

<ol start="2">

 <li>Write and test a set of SQL statements that will create the following tables:

  <ol>

   <li>Engineers</li>

  </ol></li>

</ol>

Primary Key: EID

Columns: Lastname, Firstname, Email, Graddate

<ol>

 <li>Faculty</li>

</ol>

Primary Key: FID

Columns: Lastname, Firstname, Email, Hiredate

<ol>

 <li>Classes</li>

</ol>

Primary Key: CID

Columns: Subject (e.g. SDEV), Catalognbr (e.g. 350), Title (e.g Database Security ) d. ClassEnrollments

Primary Key: EnID

Foreign Keys:  CID (from Classes), FID (from Faculty), EID (from Engineers)

Be sure table and column names <strong>exactly</strong> match the requirements.

<ol start="3">

 <li>Write and test a set of SQL statements that will insert the following quantity of records into each table

  <ol>

   <li>15 Engineers</li>

   <li>3 Faculty</li>

   <li>3 Classes</li>

   <li>15 ClassEnrollments</li>

  </ol></li>

</ol>

Your Primary Key IDs should always start with 1 and increment by 1. You can use an Oracle sequence but it is not required. Just hardcoding the Primary Key ID is Okay for this exercise.

<ol start="4">

 <li>Write and test a set of SQL statements that will select <strong>all</strong> records from <strong>each</strong> The output should display the records in <strong>descending</strong> order by Primary key.</li>

</ol>




<ol start="5">

 <li>Write and test a set of SQL statements that will Update records with the following specifications

  <ol>

   <li>Update the Lastname of one faculty in the Faculty table to be “Friendship”.</li>

   <li>Update the Firstname of one engineer in the Engineers table to be “Amadeus”.</li>

   <li>Update the Subject of one class in the Classes table to be “IOT Cyber”.</li>

  </ol></li>

</ol>

You may need to use these requirements as you design your insert statements for step 3.

<ol start="6">

 <li>Write and test a SQL statement that will Delete the ClassEnrollments record with the lowest EnID</li>

</ol>




<ol start="7">

 <li>Write and test a SQL statement that creates a <strong>view</strong> joining the required tables such that a user can retrieve the Engineer’s Lastname and Firstname, the Faculty Lastname and Email and the Classes’s Subject and Title for each Course enrollment.</li>

</ol>


