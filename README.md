# Components
- index.php is used as the signin page.
- signup.php is used to signup a student for the very first time.
- forgotpassword_email is used to reset password of existant student user, using registered student email address.
- forgotpassword_mobile is used to reset password of existant student user, using registered student mobile number.
- registration.php is used to register more details of students.
- documents.php is used to register documents of students.
- profile.php is used to show and edit students profile, which include all details of students.
# Features 
 - if username dosent match with corresponding password then an error is raised
 - if username already exist then it will give warning.
 - password have rules as follow:
1. Must contain at least one number
2. one uppercase and lowercase letter
3. at least 8 or more characters
 - if password and confirm password dosen't match, then it gives warning.
 -  forgot password can be done using 2 ways as follows:
1. using email
2. using mobile number
 - student login, student registration and student documents table is maintained in mysql database.
 - any document uploded to database will also be stored in images folder.
 - profile page is used to edit the student's details if necessary.
