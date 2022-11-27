# HTTP 5112 Cumulative 2

## Database:
- [/Models/SchoolDbContext.cs](HTTP5112_Cumulative_2/Models/SchoolDbContext.cs)
- A class which connects to MySQL school database

## CSS:
- [/wwwroot/css/site.css](HTTP5112_Cumulative_2/wwwroot/css/site.css)
- CSS file for the whole site

## JavaScript:
- [/wwwroot/js/site.js](HTTP5112_Cumulative_2/wwwroot/js/site.js)
- JavaScript file for the whole site
- Validate the user inputs in Teacher's New Page by regular expression to ensure that the user doesn’t accidentally submit a form with missing/incorrect information

## Home:
![The layout of the Home Page](https://raw.githubusercontent.com/ceciaups/HTTP5112_Cumulative_2/master/HTTP5112_Cumulative_2/Capture/home.png)
- [/Views/Home/Index.cshtml](HTTP5112_Cumulative_2/Views/Home/Index.cshtml)
- Home page leads to other pages (teacher, student and class)

## Teacher:
![The layout of the Teacher Page](https://raw.githubusercontent.com/ceciaups/HTTP5112_Cumulative_2/master/HTTP5112_Cumulative_2/Capture/teacher.png)
![New Application of the Teacher Page](https://raw.githubusercontent.com/ceciaups/HTTP5112_Cumulative_2/master/HTTP5112_Cumulative_2/Capture/new.png)
| Type | Description | File |
| --- | --- | --- |
| Controller | A WebAPI Controller which accesses information about teachers | [/Controllers/TeacherDataController.cs](HTTP5112_Cumulative_2/Controllers/TeacherDataController.cs) |
| Controller | A Controller which routes to List/Show/DeleteConfirm/New Pages | [/Controllers/TeacherController.cs](HTTP5112_Cumulative_2/Controllers/TeacherController.cs) |
| Model | A Model which represents information about a teacher | [/Models/Teacher.cs](HTTP5112_Cumulative_2/Models/Teacher.cs) |
| View | A View which uses server rendering to display list of teachers' names from the MySQL Database | [/Views/Teacher/List.cshtml](HTTP5112_Cumulative_2/Views/Teacher/List.cshtml) |
| View | A View which uses server rendering to display the information of a teacher from the MySQL Database with search engine | [/Views/Teacher/Show.cshtml](HTTP5112_Cumulative_2/Views/Teacher/Show.cshtml) |
| View | A View which allows you to input information about a new teacher | [/Views/Teacher/New.cshtml](HTTP5112_Cumulative_2/Views/Teacher/New.cshtml) |
| View | A View which asks you to confirm deleting a teacher, and maintain referential integrity by updating the class(es) to point to NULL | [/Views/Teacher/DeleteConfirm.cshtml](HTTP5112_Cumulative_2/Views/Teacher/DeleteConfirm.cshtml) |

## Student:
![The layout of the Student Page](https://raw.githubusercontent.com/ceciaups/HTTP5112_Cumulative_2/master/HTTP5112_Cumulative_2/Capture/student.png)
| Type | Description | File |
| --- | --- | --- |
| Controller | A WebAPI Controller which accesses information about students | [/Controllers/StudentDataController.cs](HTTP5112_Cumulative_2/Controllers/StudentDataController.cs) |
| Controller | A Controller which routes to List/Show Pages | [/Controllers/StudentController.cs](HTTP5112_Cumulative_2/Controllers/StudentController.cs) |
| Model | A Model which represents information about a student | [/Models/Student.cs](HTTP5112_Cumulative_2/Models/Student.cs) |
| View | A View which uses server rendering to display list of students' names from the MySQL Database | [/Views/Student/List.cshtml](HTTP5112_Cumulative_2/Views/Student/List.cshtml) |
| View | A View which uses server rendering to display the information of a student from the MySQL Database with search engine | [/Views/Student/Show.cshtml](HTTP5112_Cumulative_2/Views/Student/Show.cshtml) |

## Class:
![The layout of the Class Page](https://raw.githubusercontent.com/ceciaups/HTTP5112_Cumulative_2/master/HTTP5112_Cumulative_2/Capture/class.png)
| Type | Description | File |
| --- | --- | --- |
| Controller | A WebAPI Controller which accesses information about classes | [/Controllers/ClassDataController.cs](HTTP5112_Cumulative_2/Controllers/ClassDataController.cs) |
| Controller | A Controller which routes to List/Show Pages | [/Controllers/ClassController.cs](HTTP5112_Cumulative_2/Controllers/ClassController.cs) |
| Model | A Model which represents information about a class | [/Models/Class.cs](HTTP5112_Cumulative_2/Models/Class.cs) |
| View | A View which uses server rendering to display list of classes' codes from the MySQL Database | [/Views/Class/List.cshtml](HTTP5112_Cumulative_2/Views/Class/List.cshtml) |
| View | A View which uses server rendering to display the information of a class from the MySQL Database with search engine | [/Views/Class/Show.cshtml](HTTP5112_Cumulative_2/Views/Class/Show.cshtml) |
