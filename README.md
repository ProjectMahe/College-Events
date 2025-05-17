# College-Events

Role Based Access Control System
1. Admin
2. Teacher
3. Coordinator
4. Student

Frontend: HTML, CSS, Javascript, React
style.css

Pages for Admin-
admin.css
adminregister.html (option)
adminlogin.html
admindashbord.html
teacherview.html
coordinatorview.html
studentview.html

adminlogout.html

Pages for Teacher-
teacher.css
teacherregister.html
teacherlogin.html
teacherdashbord.html
teacherlogout.html

Pages for Coordinator-
coordinator.css
coordinatorregister.html
coordinatorlogin.html
coordinatordashbord.html
coordinatorlogout.html

Pages for Student-
student.css
studentregister.html
studentlogin.html
studentdashbord.html
studentlogout.html

Backend: Python Django,

Database: 



Updated Permissions per Role:

Action	Admin	Faculty	Student	Event Coordinator

Create Event	Yes	Yes	No	Yes
Edit Event	Yes	Own	No	Own
Delete Event	Yes	Own	No	Own
View Events	Yes	Yes	Yes	Yes
Approve/Reject Events	Yes	No	No	No
Register for Event	No	No	Yes	No
View Registered Students	Yes	Yes	Own	Yes

