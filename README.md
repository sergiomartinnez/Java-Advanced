# Advanced Java

## Table of Contents
* [General info](#general-info) 
* [Technologies](#technologies) 
* [Setup](#setup)
* [Extra information](#Extra)

------------
## General info

In this course i reviewed all the topics of java-oop and OOP previous courses, in the files you will find the project amazonviewer, basically pretends to be an interactive interface for watching movies, series, read books magazines, etc. and you can check it as read or seen if you have watched it, the code will record it and generate you a report status of the things that have you seen already, adding this information to database and generating new objects on the database.

------------
## Technologies

>- Eclipse 2021-06
>- MYSQL 8.0.25
>- XAMPP 8.0.7

------------
## Setup
This project was made on a Windows 10 OS.

### eclipse 
1. Go to https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2021-06/R/eclipse-inst-jre-win64.exe
2. Click to Download and follow the steps with the program for installation

### MYSQL 8.0.25
1. go to https://dev.mysql.com/downloads/connector/j/
2. Click on "go to download page" 
3. click on sign up on oracle for download the program
4. download either web community or community program 
5. proceed the installation with the program.

### XAMPP 8.0.7 
1. go to https://www.apachefriends.org/es/index.html
2. click on download in your preferred operating system
3. proceed the installation with the program.


------------
## Extra

>- abstract classes
>- interfaces
>- javadoc (@author, @verion, @link, @since, @see
>- nested classes (static and non static classes)
>- DAO interface (data access object) allow us to get more methods like CRUD (create, read, update and delete)
>- error managment (throwable) for adding a code block for handle an error
>- error, exception (runtime, IOEexception) types of throwables}
>- try catch finally here it goes the code block that is vulnerable
>- try with resources close the resource flow by his own.
>- JDBC as an API complex
>- drivermanager, connection, statement, preparedstatement, resultset
>- lambdas allow us to pass a function to another function, like chain of functions and is used for short life code
>- AtomicInteger generate atomic integer number
>- stream handle lambdas in collections
>- filter filter the collection 
>- predicate interface that declare lambdas and adds them to variables
>- consumer interface that iterates all we want to handle in the foreach

------------
### commands that i learned
|  Command | Function  |
| ------------ | ------------ |
|  try{} catch {} finally {} | code block that is vulnerable |
|  try with resources | close the resource flow by his own |
|  DriverManager | reates an instance of the connection (takes the already included jar and generate the connection) |
|  Connection | generates the session and stores it as long as we are connected (life cycle) |
|  Statement | they are the key to query data, it helps us to bring data from a specific table |
|  PreparedStatement | they are the key to query data, receive parameters inside the where clause |
|  resultSet | interface to handle the data obtained from the database, handles and extracts data to pass it as a unique and distinct object |
|  Lambdas (parameters) -> {body-lambda (here goes the commands)} | allow us to pass a function to another function, like chain of functions and is used for short life code |
|  Lambdas as variable Listener listener = (parameters) -> {body-lambda} | used for define variables |
|  atomicInteger | generates atomic integer number |
|  stream | handle lambdas in collections |
|  filter | filter the collection |
|  predicate ex. predicate<”class”>  predicate = s -> s.getisviewed(); | interface that declare lambdas and adds them to variables |
|  consumer ex. Consumer<class> seriesEach = s-> contentReport.append(s.toString() + "\n"); | interface that iterates all we want to handle in the foreach |

