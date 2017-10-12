# Table
CREATE table Student_Information6(Registration_number INTEGER PRIMARY KEY, Student_name TEXT, Grade TEXT, Age INTEGER, Marks DEC, Class_teacher TEXT, Parents_name TEXT);

CREATE TABLE Parents (Registration_number INTEGER PRIMARY KEY, Father_name TEXT, Mother_name TEXT, Father_phone_number TEXT, Mother_phone_number TEXT,Father_email TEXT,Mother_email TEXT, Father_profession TEXT, Mother_profession TEXT, emergency_contact TEXT);

CREATE TABLE attendance(Registration_number INTEGER PRIMARY KEY PRIMARY KEY, student_name TEXT, Tdate DATE, atten BOOLEAN);

INSERT INTO Student_Information6 values(123004, "Daniel", "11  Sci", 16, 100, "Mrs.Berek", "Mr and Mrs.Long");

INSERT INTO Parents VALUES (123004," John", "Mary", "725272825","282372692","john.long@gmail.com", "mary.long@gmail.com"," Manager"," Designer",  "2761836127");

INSERT INTO attendance VALUES (123004,"Daniel","25/08.01",TRUE);
