Download Link: https://assignmentchef.com/product/solved-csi121-lab5-java-text-file-i-o-and-object-serialization
<br>
<strong>Objectives</strong>

<ul>

 <li>Familiar with Java text file I/O and object serialization.</li>

</ul>

In Assignment 2, both the Bachelor and Master of Computer Science course structures are inputted manually inside the main() method. The students’ enrolment records cannot be kept as well. In Lab 5, you are asked to modify the A2’s solution by using the object serialization and file I/O to import/export course objects and export the students’ enrolment records to a text file.

<strong><u>Tasks:</u> </strong>

Task 1:

<ol>

 <li>Modify the existing Course, Subject and Major classes by implementing the serializable interface;</li>

 <li>Create a new primary class (CreateCourse) without any class field;</li>

 <li>Use the ObjectOutputStream class in the main() method of CreateCourse class to output the Bachelor of Computer Science course object to a binary file named ser (within the same directory as the CreateCourse.java) and the Master of Computer Science course object to a binary file named mcs.ser.You shall re-use the hardcode in A2’s solution to create all subject, major and course objects first. Then use the writeObject() method to export the two course objects to two binary files, respectively.</li>

</ol>

Task 2:

<ol>

 <li>Update the StudentSystem class in A2’s solution (you can use your or my A2 solution) with the exception handling process completed in Lab 4;</li>

 <li>Update the StudentSystem class and use the ObjectInputStream class to import the Bachelor of Computer Science course object and the Master of Computer Science course object from the binary files <em>bcs</em>.ser and ser (created in Task 1), respectively;</li>

 <li>Enrol two students to BCS and MCS course respectively (exactly same process as A2);</li>

 <li>Export all students’ enrolment record information (the exactly same information displayed on the screen after the completion of the two students’ enrolment in A2) into a text-file named txt (within the same directory as the StudentSystem.java). You must use the Formatter class and the format() method.</li>

</ol>


