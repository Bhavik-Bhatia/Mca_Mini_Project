# Mca_Mini_Project
This is the Mini project for MCA, semester 3.

#Login Details

1)Student Login is done using Firestore db while Admin Login is done using Firebase Auth.
2)Because whenever you use Auth you get ID of the current Instance but as we have provided a feature to Admin to add students, as Admin is logged In we won't get the
ID of students as Instance is of the Admin.

#Steps of Login

1)username password added, Admin Boolean
2)Depending on Admin Boolean if yes -> Authentication if Admin is trying to login
3)If it is student go to Student_profile and check for details

#Steps of SignUp(Student)-

1)Fill details 
2)Perform Password Encryption
3)Store details in Student_Profile
