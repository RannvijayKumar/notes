- 29/04/2020
- Wednesday
- Day 2


- Microservices
- Divide the work between
- Flow



# Microservices

- Monolothic arch all code is in a single place

- Dividing Monolithic into different services


- Employee Management - Monolithic
    - Packages
        - Classes
            - Functions

- Microservices
    - If one part of the application breaks, the whole application doesn't go down

- Monolithic
    - If one part breaks, everything breaks


- ```monolith.exe```
    - Complete projects

- ```microservice1.exe``` 
    - start parts of projects
- ```microservice2.exe```
- ```microservice3.exe```


- Monolith
    - all code of your project is started via a single executable

- Microservices
    - All parts of our projects have their own executable
    - syntax error in f1
        - only the micrservice which has that function will go down

- DevOps
- Cloud Computing
- CI/CD
- Containerization
- Microservices


- Microsoft
    - Ship first, test later


- The early bird takes the prey
- The first one to market has the upperhand

- Agility
    - The faster you are, the more profits you will earn



- DevOps
    - continuous development
    - continuous operations
        - Add something everyday

    - Integrate functionalities and process
        - 2 Different functionalities = 2 People
    
    - Development + Operations


- Team Project
    - College
        - Development
        - Operations
        - Manage the project the way I like


- One Man Army
    - There are no collisions
    - No room of compromise
    - Overburdened
- Team Work
    - Faster, if everyone puts efforts
    - Collisions, they resolve over time
    - People learn to work with other over time
- Cross Team Work
    - Even Less optimized


- Pre-DevOps Organizations
    - Development Team/Coders  3  
        - Code
    - Operations Team/IT <- no value   30    
        - Deploy
        - Service Managent
        - Laptops
        - Maintain OS patches
        - Help Desk
    - Testing Team      1    
    - HR Team           1   
    - Project Management/Architect 1 

- Project
    - 3 Dev
    - 2 IT
    - 1 Testers
    - 1 HR
    - 1 PM

- Human Errors


- Day 7
    - Development released first version
- Day 10-13
    - Try to deploy
    - It failes to deploy
    - send back to developers
- 16-20
    - Developers get
- 22
    - It finally gets deployed


- Project
    - Development
    - Operations
    - Testing
    - QA
    - HR
    - PM


- Teams - 1 or more
    - 1 HR
    - 2 Developers
    - 1 Operations
    - 1 Testing
    - 1 Security
    - 1 PM

- DevOps: do you think devops sounds cool?
- 2009: Organized DevOpsDays: because he thought the name was cool
    - Collectively put it as DevOps, because they discussed these things on DevOpsDays whose name was **cool**
    - DevOps was called so just because it was 

- What was the effect of the name "DevOps" in past 11 years?
    - Blog Post Writers
        - The first one wins the view count
        - SEO
            - The oldest page has a good priority
    - Developers + Operations
        - DevOPs to be Dev+Ops
    - Companies
        - They will start creating tools which optimize the interaction between developers and operations
    - Consumers
    - Budding Developers
    - CNCF
        - Cloud Native Computing Foundation
    - alldaydevops


- 5 days
- 3 Days

7 * 3 Days

21 Days



- 7 days






- H.W.
    - For your Projects
        - Find out the development part and the operations part



# Agenda

- Microservices - Theory
- Flow in general
- Divide the Work





- To work with an Application
    - GUI
    - CLI
    - Network

- Protocol 
    - TCP/UDP
    - Application Layer: HTTP, FTP, 
- ip address
- port number




- Benefits of Microservices
    - Fault Tolerant
    - Abstraction
    - Easier to Understand, Write, and keep track to code
    - Loose Coupling
    - Flexibility
    - Faster to (re)deploy
    - Easier to (re)deploy
    - Compilation 
    - DevOps Optimized


- Hurdles for Microservices over Monolithic
    - Think about the communication
        - Protocol TCP/https
        - IP    DNS will give me IP
        - Port  443
        - Solved by Eureka
    - Difficult to monitor and logging
        - logger - dumping logging
        - prometeus - centralized monitoring
        - elastic search - manual analyisis
    - Difficult for developer to locate microservices
        - Eureka
    - Difficult for end user to access functionality spread throughout microservices
        - Angular 
        - Feign
    - Difficult to locate microservice
        - Eureka
    - Difficult to Scale up and Down
        - Ribbon
    - Difficult to deploy
        - Kubernetes
        - IaC
        - Consul
        - Service Meshes
        - knative
        - Cloud COmputing
        - Containerization
        - CI/CD
    - Difficult to Operate
        - Swagger 


- Pioneered the Microservices architecture without even realizing it
    - Martin Fowler who coined


- Build Time
    - 10 GB
        - Faster for the first time
    - 10 * 1 GB
        - Slower for the first time
    - 1 GB
        - Rebuilding a single microservice is faster



DNS : Name - IP
Service Discovery: Name -> IP:Port





https://thenewstack.io/ebooks/serverless/guide-to-serverless-technologies/
https://thenewstack.io/ebooks/index.html


Literal

virtual URI

Application routing

```webapp/ebooks/index.html```




- Do I need 100 domains?


- Domain -> 1 Service



localhost/cart/add
localhost/payment/add


100 Microservices
1 Domain



1 Server
    - 1 CPU
    - 2 GB


- Vertical Scaling
    - 2 CPU
    - 4 GB
- Horizontal Scaling
    - 2 Servers
        - 1 CPU each
        - 2 GB RAM Each
        - 2 Microservices
        - 2 IP Address
        - 2 POrts

    - Application Load Balancer
        - Whenever I get a requests
        - 2 Microservices


- Problem Statement
    - 3 Times,  3 IP 3Port


- Proxy
    - path : IP-port
    - path : Name M1


    /payment : N
    N : M1


fil
- /api/profile/add

```json
{
    "name":"Faiz",
    "occuputaion": "trainer"
}
```


- /api/employee/add

```json
{
    "name":"Himali",
    "empID": 32
}
```



100 Microservices



- How Many Microservices should we split our project into
- What code goes to which microservice 
- Flow
    - Make your previous project working
    - Refine your Models
    - For your projects speculate what kind of microservices can you break into
        - Microservice design principle
- How to integrate all micrservices
    - Eureka
    - Zuul
        - Ribbon
        - Feign
- Integration Front-end and Back end




- Bandwidth Issues:
    - 4 hrs a day
    - 1GB/day



- Microservice 1
    - add  transaction
    - delete transaction
    - read transaction
    - modify transaction
- Microservice 2
    - add  employee
    - delete employee
    - modify employee
    - read employee


- Ecommerce
    - Shopping Cart
        - Discount on Payment Methods
            - Communication
    - Payment
        - Credit Card
        - Online Banking
        - UPI
    - Orders
    - Customer Details

- API
    - Input
    - Output

- Functional Requirements
    - Technical Solutions


- Business Requirements
    - That will get you money
    - Offers
    - Discounts
    - sale

# Final Homework

- Flow
    - Make your previous project working
    - Refine your Models
    - For your projects speculate what kind of microservices can you break into
        - Microservice design principle