# Mca_Mini_Project
This is the Mini project for MCA, semester 3.

#Login Details

1)Student Login is done using Firestore db while Admin Login is done using Firebase Auth.
2)Because whenever you use Auth you get ID of the current Instance but as we have provided a feature to Admin to add students, as Admin is logged In we won't get the
ID of students as Instance is of the Admin.

#Steps of Login(Done)

1)username password added, Admin Boolean
2)Depending on Admin Boolean if yes -> Authentication if Admin is trying to login
3)If it is student go to Student_profile and check for details

#Steps to remember Authentication

1)For Admin Firebase Auth will help.
2)For Student you need to store email, isLogin bool in SQLlite and with logout you need to update isLogin bool as false.

#Steps for Splash Screen

1)Check for Admin in FirebaseAuth:true - > Dashboard, FirebaseAuth:false - > Login
2)Check for SQLite for isLogin -> true: - > Dashboard(get email from SQLite), isLogin:false - > Login

#Steps of Adding(Student) by Admin-

1)Fill details 
2)Perform Password Encryption (Initial auto-password: Password123)
3)Store details in Student_Profile

OR

1)Import CSV file and fetch details.
2)Perform Password Encryption (Initial auto-password: Password123)
3)Store details in Student_Profile

