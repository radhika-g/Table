# Table
CREATE table Student_Information6(Registration_number DOUBLE PRIMARY KEY, Student_name TEXT, Grade TEXT, Age INTEGER, Marks DEC, Class_teacher TEXT, Parents_name TEXT);

CREATE TABLE Parents (Registration_number DOUBLE PRIMARY KEY, Father_name TEXT, Mother_name TEXT, Father_phone_number TEXT, Mother_phone_number TEXT,Father_email TEXT,Mother_email TEXT, Father_profession TEXT, Mother_profession TEXT, emergency_contact TEXT);

CREATE TABLE attendance(Registration_number DOUBLE PRIMARY KEY PRIMARY KEY, student_name TEXT, Tdate DATE, atten TEXT);

INSERT INTO Student_Information6 values(123004, "Daniel", "11  Sci", 16, 100, "Mrs.Berek", "Mr and Mrs.Long");

INSERT INTO Parents VALUES (123004," John", "Mary", "725272825","282372692","john.long@gmail.com", "mary.long@gmail.com"," Manager"," Designer",  "2761836127");

INSERT INTO attendance VALUES (123004,"Daniel","25/08/01","absent");



INSERT INTO Student_Information6 values(134897, "Radha", "11  Sci", 16, 23, "Mrs.Berek", "Mr and Mrs.Tiny");

INSERT INTO Parents VALUES (134897,"Richard", "Molly", "725272827","282372632","richardtiny@gmail.com", "Molly_tiny@gmail.com","Doctor","Lawyer",  "2761836231");

INSERT INTO attendance VALUES (134897,"Radha","25/08/01","present");


INSERT INTO Student_Information6 values(126924, "Dale", "11  Sci", 15, 90, "Mrs.Berek", "Mr and Mrs.Mumford");

INSERT INTO Parents VALUES (126924," James", "Marie", "725395825","281042692","james.mum@gmail.com", "marie.mum@gmail.com","Accountant","Teacher",  "2761838457");

INSERT INTO attendance VALUES (126924,"Dale","25/08/01","absent");



INSERT INTO Student_Information6 values(134815, "Tony", "11  Sci", 16, 69, "Mrs.Berek", "Mr and Mrs.Strathford");

INSERT INTO Parents VALUES (134815,"Tom", "Mel", "725272100","282372049","tom_s@gmail.com", "mel.strath@gmail.com","Scientist","Nutritionist",  "2761838374");

INSERT INTO attendance VALUES (134815,"Tony","25/08/01","present");



INSERT INTO Student_Information6 values(132789, "Tim", "11  Sci", 17, 83, "Mrs.Berek", "Mr and Mrs. Carli");

INSERT INTO Parents VALUES (134815,"Theo", "Lorraine", "725283645","282392749","theo-c@gmail.com", "lorraine.carli98@gmail.com","Social Influencer","Chef",  "2761873823");

INSERT INTO attendance VALUES (134815,"Tim","25/08/01","present");





