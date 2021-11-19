# ExperienceShip
This program is a platform which will conect students with start-ups and companies. It aims to solve the problem where companies require high levels of experience for internship positions, which prevents students at university level from building experience. The platform will also account for issues such as Location of the job, Morning-vs-Afternoon of the job, etc...

Main functions of the platform:
  1. Students have access to database of all jobs available from companies that require little to no expereience
  2. Companies have access to database of students looking for internships

## Installation
In order for the program to work you must have the python programming language installed. Any version between Python 3.6 and 3.8 will work.

## Usage
Once entered the plaform, the platform will guide the user through anything they wish to do with no need to run seperate sections of the code every time the want to do a new action. The process the platform will go through is the following:
* Platform will ask if they are a Company or a Student
* Sign in or sign up to the platform?
* Once they have entered the platform through signing in or singing up, the will have the following options:
  * Search for specific companies/students that satisfy a specific industry/degree studied
  * Edit their profie preferences of students/jobs they are looking for
  * Look ath the top 5 students/job recommened to them based on their profile preferences
### Searching for a Company / Student
  * Input: If the current user is a company, the platform will ask for the the specific degree the want the student to have, if the current user is a student, the platform will ask for the name of the company they want to see the jobs for
    * Eg: 'BBA' or 'Amazon'
  * Output: If searching for a company, the platform will return specifications for each job offered by that company, if searching for students based on degree, the platform will return the characteristics of each student that is in the database that studies that degree
    * Characteristics returned for each job of the comapny: Name of Company, Type of Position available, Time frame of the position, Location, GPA and Degree Required
    * Characteristics returned about each student: Name, Degree Studying & University year, current GPA, job specifications they are available for
### Editing Profile
  * Display: Platform will display a list of characteristics of their profile they can edit
  * Input: User will input what they want to edit, and what the new value for that charactersitic is
  * Output: Displays the new user profile with the modified characteristic
### Top 5 Companies / Students
  * This section requires no input, there is simply an output
  * Output: Platform will display the characteristics of the top 5 job positions of which the current user's profile matches the most

## Additional Information (Specific to Final Project of Algorithms and Data Structures Class)
This program utalizes the following topics learned in class:
  1. Creation of Class Objects 'Student' and 'Company' with corresponding attributes and methods - Used to create users in the platform and allow them to perform actions such as editing profile, or finding the best jobs/students for them
  2. Heaps - Used to identify the best jobs/students for them based on the amount of characteristics the two users have in common

## Credits
The authors of this project, of both the idea development and code development are:

Ana Ocariz   
Stephanie Ros   
Sofia Gonzalez   
Diego Larrañaga   
Jose Maria Castelo   
Juan Tasende
