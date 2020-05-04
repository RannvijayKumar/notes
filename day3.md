- 30/04/2020
- Thursday
- Day 3


# Flow

- Plan
- Create a git repository
- Initialize spring boot project
- List funcitonality
- Create a Model
- Come up with routes for functionality
- Create a Skeleton with placeholders
- Return Hardcoded values







- DevOps
- Microservices
    - Drawbacks of Microservices
    - Which services would you use to solve them



2 hrs of session:
    - Implement Microservices
1 hr of discussion with each group:
    - See your progress
    - I will try to clarify your doubts

9-5:
    - I will be glad to answer your questions


- Employee Management System
    - Basic Employee Details (Current)
        - Employee ID
        - First Name
        - Last Name
        - Address
        - DOB
        - Email Address
        - Phone Number
        - Date of Joining
        - Gender
        - Marital Status
        - Years of Experience
        - Designation
        - Location
        - Department
        - Team
        - Project
    - Employee History Microservice
        - Team History
            - Year: Team
        - Project History
        - Designation History
        - Location History
        - Department History
        - Team History
    - Credential Management
        - Login Credentials
    - Employee Transaction
        - Salary
        - Salary Levels
        - Salary Deduction Details
        - Salary History
        - Reimbursements Details
    - Employee Rating
    - Bonus
    - Assets assigned
        - Return Date
    - Leave


- How you should divide microservices should reflect how your organization thinks


- CRUD operations in a single microservice
- Access controls using Spring Security



- Functions
- Modules







- HTTP Method
    - GET
    - POST
    - PUT
    - DELETE


- Create
- Read
- Update
- Delete


- CRUD 




- Design Principle
    - Business Domain Centric
        - Division on the basis of money
    - High Cohesion
        - Bundle similar functionality
    - Autonomous
        - Not to use shared resources



- Git Repositories
- DB
- REST API using Spring Boot
- Configure Spring boot with MySQL DB
    - application.properties
- MVC
    - Models
        - @Entity
        - @Component
    - Views
    - Controllers


- Spring
    - Configuration over code 
    - beans.xml
- Spring boot
    - Convention over configuration
- gulp
    - code over configuration




# Flow

- Plan
- Create a git repository
- Initialize spring boot project
- List funcitonality
- Create a Model
- Come up with routes for functionality
- Create a Skeleton with placeholders
- Return Hardcoded values



- Monolithich Application
    - Single Git Repository

- Microservices 
    - One Repository for each microservice




1 project - 10 microservices 10

- git submodules

- git repository
    - another git repository as a folder using submodules


Project git repository:
    - 10 folders which are git repositories themselves



- public repositories
- contribute to public repositories?





group: in.cg.<project name>
artifact: <microservice name>


- Models, Views, and Controllers
    - Models: Defines my Data
    - View: Represent my Data
    - Controller: Interact with my Data

- in.cg.models
- in.cg.demo.models

- convention over configuration


- Employee ID
- Name
- Age
- Email Address


- @Component
    - class
- @Entity
    - class
- @Bean
    - function


- Dependency Injection?

- 




@RestController
@Controller



# CW

- Monolothic Applications to Microservices


- Morning Session
    - Create git repositories
    - how to contribute to git repositories
    - STS and add things to git repositories
    - Best practices to connect to a db using sprint boot











# T1 : Employ Maintenance system

- Admin
    - Login with credentials
    - Add Employee Details with validations
    - Modify Employee with validation
    - Display all Employees
- Employee
    - Login with credentials
    - Search and display one
    - Apply for leave



- Login Microservice
    - Credentials for employee and admin
- CRUD Employee 
- Angular UI
    - Admin
    - Employee


High Cohesion
Business Domain Centric
Autonomous
    - 1 Microservice should not share the db


## 

1. UI
    .json
2. EmployeeCRUD
    model
    /add  
    {"":""}
    Functionality
    /delete/{id}
    METHODS
3. Leave
    model
    /add



# T2 Online Banking System

- 6 Microservices
    - UI
        - Admin
        - User
    - Login
        - Login into the system using his/her credentials.  
        - Change password
    - Account Holder Detials
        - Request for change in communication address/mobile number for bank account
    - Account Details
    - Services
        - Request for change in communication address/mobile number for bank account
        - Request for cheque book
        - Track  service request
    - Transactions              - 1 db
        - Account Statement
            - View  Mini /Detailed statement of  all the accounts (Mulitple accounts , if any can be viewed)
    - Fund Transfer

- A set of administrators are assigned for managing the system. An admin has been assigned a set of privileges to manage the system. An admin can perform the following functionalities:
- Create a new Account upon request.


- Business Domain Centric
- Autonomous
    - 1 microservice should work on one db
- High Cohesion

Microservice for admin:
    - look at all the transaction
Microservice for user: 
    - look at all the transactions for all the account he/she holds


- Identity
- Authentication
- Authorization
- Accounting



- Just works

## Tasks till Day 4

- Create Spring boot projects for every microservice
- Initialize all of them with a git repository
- Template Models
- Controller Skeleton
    - /add POST
    - return ""



- Microservice 1
    - API
- Microservice 2
    - API


- Fund Transfer
    - Source Account id
    - Money
    - Destination account id

    - Account Holder
    - Accounts
        - Account ID 1
        - Account ID 2  
        - Account ID 3

    - Account Data Retrieval
        - Account Holder ID
            - Account IDs



# T3: Bus Booking Management system

- Angular
    - UI
        - User profile page 
        - User profile & Privacy settings 
        - Sorting Bus Details
        - Modify Search
    - Admin
        - add Route/Bus
- Microservices
    - User/Login Microservices
        - sign up
        - Login/Logout/session 
        - Password encryption 
        - Change password 
        - Forget password 
        - Privacy Settings
    - User Accounts
        - Booking Details
        - Generate reports
        - Update bus Details
    - City 
    - Bus
        - CRUD Bus
        - Sorting Bus Details
        - Seat availability
        - Bus rating
        - Route
            - Add Route
    - Bookings
        - Advance Bus
        - Bus Booking
        - Generate Ticket
        - Cancel Booking
            - Refund Money
        - Display fare
        - Booking Details
        - Give feedback
    - Transactions Microservice
        - Refund Money


- Create Spring boot projects for every microservice
- Initialize all of them with a git repository
- Template Models
- Controller Skeleton
    - /add POST
    - return ""









# T4 Real Estate

- Create Spring boot projects for every microservice
- Initialize all of them with a git repository
- Template Models
- Controller Skeleton
    - /add POST
    - return ""


- signup   - User Model 
- create/update profile - Profile 
- search flats, villa, appartment, plots   Property
- buy/sale
- Analysis Report Model


- User: Properties looked at
- User: properties brochure downloaded for 



sign up
Login/Logout/session 
Password encryption 
Change password 
Forget password 
User profile & Privacy settings 
Search Property
View Image
Download Brochure
Business Analysis
Admin Notification
Reporting Analysis
home/profile page - integration 