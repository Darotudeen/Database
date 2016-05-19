QUERIES
-------
---->SELECT ID, First Name, Grade, FROM SCORE CARD
     /*shows all information on the score card table with ID, Firstname, Grade columns respectively*/

---->SELECT COUNT(*), FROM SCORE CARD 
     WHERE Grade = A
     /* shows the number of Grade column that has the A-input*/

---->SELECT COUNT(*), FROM SCORE CARD 
     WHERE Score = 30
     /* shows the number of score columns with score of 30 */

---->INSERT INTO APPLICANTS' STATISTICS (ID, Sex, Religion,)
     VALUES (1, "Male", "Islam")
     /*Adds inputs (1, "Male", Islam)into the column (ID, Sex, Religion) respectively 
      inside APPLICANT STATISTICS TABLE*/

----->UPDATE SCORE CARD
      SET First Name ='Darot', Last Name='Peacedude'
      WHERE First Name = 'Andela', Last Name = 'Boot-camp'
      /*Changes the First Name and Last Name column that holds the name 'Andela' and Boot-camp'
       into 'Darot' and 'Peacedude' respectively*/
 