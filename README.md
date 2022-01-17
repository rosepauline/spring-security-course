1.bootstrap-build an API: 
Go to browser and run,
http://localhost:8080/api/v1/students/1

2.Installing spring boot security:
Run the application,
Go to browser and hit http://localhost:8080/api/v1/students/1
Enter userName as "user" and password from the terminal(Using generated security password: 8de08c55-c3fe-4842-8f59-e5edf587b6f6)
{"studentId":1,"studentName":"James Bond"}
login:http://localhost:8080/login
logout:http://localhost:8080/logout

3.Basic authentication:
No way to logout. username and password is sent in every singe request.
Go to browser and hit http://localhost:8080/api/v1/students/1
Enter userName as "user" and password from the terminal(Using generated security password: 8de08c55-c3fe-4842-8f59-e5edf587b6f6)
{"studentId":1,"studentName":"James Bond"}

