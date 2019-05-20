## Python - 100 days from novice to master

> Author: Luo Hao

### Python application area and employment situation analysis

Simply put, Python is an "elegant", "clear", "simple" programming language.

 - The learning curve is low and non-professionals can get started
 - Open source system with a strong ecosystem
 - Interpretative language, perfect platform portability
 - Support for object-oriented and functional programming
 - Ability to extend functionality by calling C/C++ code
 - High code specification and readability

Python is currently used in several popular areas.

 - Cloud Infrastructure - Python / Java / Go
 - DevOps - Python / Shell / Ruby / Go
 - Web crawler - Python / PHP / C++
 - Data Analysis Mining - Python / R / Scala / Matlab
 - Machine Learning - Python / R / Java / Lisp

As a Python developer, the main areas of employment include:

- Python server background development / game server development / data interface development engineer
- Python automated operation and maintenance engineer
- Python Data Analysis / Data Visualization / Big Data Engineer
- Python crawler engineer
- Python Chat Robot Development / Image Recognition and Vision Algorithm / Deep Learning Engineer

The chart below shows the Python recruitment requirements and salary rankings for major cities (as of May 2018).

![Python recruitment requirements and salary treatment Top 10] (./res/python-top-10.png)

![](./res/python-bj-salary.png)

![](./res/python-cd-salary.png)

Several tips for beginners:

- Make English as your working language.
- Practice makes perfect.
- All experience comes from mistakes.
- Don't be one of the leeches.
- Either stand out or kicked out.

### Day01~15 - [Python Language Basics] (./Day01-15)

#### Day01 - [First Python] (./Day01-15/Day01/First Python.md)

- Introduction to Python - History of Python / Advantages and Disadvantages of Python / Application Areas of Python
- Setting up a programming environment - Windows environment / Linux environment / MacOS environment
- Run Python program from terminal - DOS command / Hello, world / print function / Run program
- Using IDLE - Interactive Environment (REPL) / Writing multiple lines of code / Running programs / Exiting IDLE
- Comments - Effect of comments / Single line comments / Multi-line comments

#### Day02 - [Language Elements] (./Day01-15/Day02/Language Elements.md)

- Programs and hexadecimal - Commands and Programs / Von Neumann / Binary and Decimal / Octal and Hex
- Variables and types - Naming of variables / Use of variables / Input function / Checking variable type / Type conversion
- Numbers and strings - Integer / Float / Plural / String / String Basic Operations / Character Encoding
- Operator - Mathematical Operator / Assignment Operator / Comparison Operator / Logical Operator / Identity Operator / Operator Priority
- Application case - Fahrenheit temperature converted to Celsius / Enter the radius of the circle to calculate the perimeter and area / Enter the year to determine whether it is a leap year

#### Day03 - [Branch Structure] (./Day01-15/Day03/Branch Structure.md)

- Application scenario of branch structure - Condition / Indent / Code block / Flow chart
- if statement - simple if / if-else structure / if-elif-else structure / nested if
- Application case - User authentication / English unit exchange with metric unit / Roll dice to decide what to do / Percentage grade to grade system / Segment function evaluation / Enter the length of three sides If you can form a triangle, calculate the circumference and area

#### Day04 - [Cycle Structure] (./Day01-15/Day04/Cycle Structure.md)

- Application of the loop structure - Condition / Indent / Code Block / Flowchart
- while loop - basic structure / break statement / continue statement
- for loop - basic structure / range type / branch structure in loop / nested loop / early end program
- Application case - 1~100 summation / judge prime number / guess number game / print ninety nine table / print triangle pattern / monkey eat peach / hundred money hundred chicken

#### Day05 - [summary and practice] (./Day01-15/Day05/summary and practice.md)

- Basic exercises - Daffodil number / Perfect number / Five people fish / Fibonacci series / palindrome
- Comprehensive Practice - Craps Gambling Game

#### Day06 - [Use of functions and modules] (./Day01-15/Day06/ Function and module usage.md)

- The role of the function - Bad taste of the code / Encapsulation of function modules with functions
- Define function - def statement / function name / parameter list / return statement / call custom function
- Calling functions - Python built-in functions / importing modules and functions
- Function parameters - default parameters / variable parameters / keyword parameters / named keyword parameters
- the return value of the function - no return value / return a single value / return multiple values
- Scope issues - local scope / nested scope / global scope / built-in scope / scope-related keywords
- Using module management functions - the concept of modules / how to manage functions / naming conflicts with custom modules (same module and different modules)

#### Day07 - [String and common data structure] (./Day01-15/Day07/string and common data structure.md)

- Use of strings - Calculate length / subscript operations / slicing / common methods
- List basic usage - Define list / Access elements with subscript / Subscript out of bounds / Add element / Delete element / Modify element / Slice / Loop traverse
- List common operations - connect / copy (copy elements and copy arrays) / length / sort / reverse / find
- Generate list - Create a list of numbers with range / Generate expression / Generator
- Use of tuples - Define tuples / Use values ​​in tuples / Modify tuple variables / Tuples and list conversions
- Collection basic usage - Differences between collections and lists / Creating collections / Adding elements / Deleting elements / Emptying
- Collection common operations - intersection / union / difference set / symmetric difference / subset / super set
- Basic usage of the dictionary - Features of the dictionary / Creating a dictionary / Adding elements / Deleting elements / Value / Clearing
- Common operations of the dictionary - keys () method / values ​​() method / items () method / setdefault () method
- Basic exercises - Marquee effect / List to find the largest element / Average score of statistical test scores / Fibonacci series / Yang Hui triangle
- Comprehensive case - Two-color ball selection / Tic Tac Toe

#### Day08 - [Object-Oriented Programming Fundamentals] (./Day01-15/Day08/Object-Oriented Programming Fundamentals.md)

- Classes and objects - What are classes / What are objects / Object-oriented other related concepts
- Define classes - Basic structure / Properties and methods / Constructor / Destructor / \_\_str\_\_ method
- Use objects - Create objects / Send messages to objects
- Four pillars of object orientation - abstract / encapsulation / inheritance / polymorphism
- Basic exercises - Defining student classes / Defining clock classes / Defining graphics classes / Defining car classes

#### Day09 - [Object-Oriented Advanced] (./Day01-15/Day09/Object-Oriented Advanced.md)

- Properties - Class Properties / Instance Properties / Property Accessor / Property Modifier / Property Remover / Using \_\_slots\_\_
- methods in classes - instance methods / class methods / static methods
- Operator overloading - \_\_add\_\_ / \_\_sub\_\_ / \_\_or\_\_ /\_\_getitem\_\_ / \_\_setitem\_\_ / \ _\_len\_\_ / \_\_repr\_\_ / \_\_gt\_\_ / \_\_lt\_\_ / \_\_le\_\_ / \_\_ge\_ \_ / \_\_eq\_\_ / \_\_ne\_\_ / \_\_contains\_\_
- the relationship between classes (objects) - association / inheritance / dependencies
- Inheritance and polymorphism - What is inheritance / inheritance syntax / call parent class method / method override / type decision / multiple inheritance / diamond inheritance (diamond inheritance) and C3 algorithm
- Integrated case - Payroll settlement system / Book automatic discount system / Custom score class

#### Day10 - [Graphical User Interface and Game Development] (./Day01-15/Day10/Graphical User Interface and Game Development.md)

- Develop a GUI using tkinter
- Develop game apps using the pygame tripartite library
- "Big ball eating ball" game

#### Day11 - [Files and Exceptions] (./Day01-15/Day11/Files and Exceptions.md)

- Read file - read entire file / line by line read / file path
- Write file - Overwrite write / Append write / Text file / Binary file
- Exception Handling - Importance of Exception Mechanism / try-except code block / else code block / finally code block / built-in exception type / exception stack / raise statement
- Data persistence - CSV file overview / csv module application / JSON data format / json module application
- Comprehensive case - Lyrics analysis

#### Day12 - [String and regular expression] (./Day01-15/Day12/string and regular expression.md)

- String advanced operations - escape characters \ original strings \ multi-line strings \ in and not in operators \ is the beginning of the method \ join and split methods \ strip related methods \ pyperclip module \ invariant string and variable String \ use of StringIO
- Getting Started with Regular Expressions - The Role of Regular Expressions \ Metacharacters \ Escapes \ Quantifiers \ Grouping \ Zero Width Assertions \ Greedy Matches and Lazy Matches Lazy \ Use re modules to implement regular expression operations (match, search, replace, capture)
- Use regular expressions - re module \ compile function \ group and groups method \ match method \ search method \ findall and finditer methods \ sub and subn methods \ split method
- Application case - validate the input string using regular expressions

#### Day13 - [Process and Thread] (./Day01-15/Day13/Process and Thread.md)

- The concept of processes and threads - What is a process / What is a thread / multi-threaded application scenario
- Use process - fork function / multiprocessing module / process pool / interprocess communication
- Use thread - thread module / threading module / Thread class / Lock class / Condition class / thread pool

#### Day14-A - [Getting Started with Network Programming] (./Day01-15/Day14-A/Getting Started with Network Programming.md)

- Computer Network Fundamentals - History of Computer Networks / "TCP-IP" Model / IP Address / Port / Protocol / Other Related Concepts
- Network Application Architecture - "Client-Server" Architecture / "Browser-Server" Architecture
- Python Network Programming - Socket Concept / Socket Module / Socket Function / Create TCP Server / Create TCP Client / Create UDP Server / Create UDP Client / SocketServer Module

#### Day14-B - [Network Application Development] (./Day01-15/Day14-B/Web Application Development.md)

- Access to the web API - Network API overview / Access URL / requests module / Parsing JSON format data
- File Transfer - FTP Protocol / ftplib Module / Interactive FTP Application
- Email - SMTP Protocol / POP3 Protocol / IMAP Protocol / smtplib Module / poplib Module / imaplib Module
- SMS service - twilio module / domestic SMS service

#### Day15 - [Image and Document Processing] (./Day01-15/Day15/Image and Office Document Processing.md)

- Process pictures with Pillow - Image read / write / Picture composition / Geometric transformation / Color conversion / Filter effect
- Reading and writing Word documents - Handling of text content / Paragraph / Header and footer / Style processing
- Read and write Excel files - xlrd module / xlwt module
- Generate PDF files - pypdf2 module / reportlab module

### Day16~Day20 - [Python Advanced] (./Day16-20/Python Advanced.md)

- Common data structures
- Advanced usage of functions - "First Class Citizen" / Higher Order Functions / Lambda Functions / Scope and Closure / Decorator
- Object-oriented advanced knowledge - "Three pillars" / Relationship between classes and classes / Garbage collection / Magic properties and methods / Mixing / Metaclasses / Object-oriented design principles / GoF design patterns
- Iterators and generators - related magic methods / two ways to create generators /
- Concurrent and asynchronous programming - Multithreading / Multiprocessing / Asynchronous IO / async and await

### Day21~30 - [Web Front End Getting Started] (./Day21-30/Web Front End Overview.md)

- Host page content with HTML tags
- Render pages with CSS
- Handling interactive behavior with JavaScript
- jQuery getting started and improving
- Getting started with Vue.js
- Use of Element
- Use of Bootstrap

### Day31~35 - [Play Linux Operating System] (./Day31-35/Play Linux Operating System.md)

- Operating system history and Linux overview
- Linux basic commands
- Utilities in Linux
- Linux file system
- Vim editor application
- Environment variables and shell programming
- Software installation and service configuration
- Network access and management
- Other related content

### Day36~40 - [Database Basics and Advanced] (./Day36-40)

- [Relational database MySQL] (./Day36-40/relational database MySQL.md)
  - Relational database overview
  - MySQL installation and use
  - Use of SQL
    - DDL - Data Definition Language - create / drop / alter
    - DML - Data Manipulation Language - insert / delete / update / select
    - DCL - Data Control Language - grant / revoke
  - related information
    - Paradigm theory - the guiding ideology for designing two-dimensional tables
    - Data integrity
    - Data consistency
  - Operate MySQL in Python
- [NoSQL Getting Started] (./Day36-40/NoSQL Getting Started.md)
  - NoSQL overview
  - Redis overview
  - Mongo overview

### Day41~55 - [Dwargo Django] (./Day41-55)

#### Day41 - [Quick Start] (./Day41-55/01. Quick Start. md)

- Web application working principle and HTTP protocol
- Overview of the Django framework
- 5 minutes to get started quickly
- Use view templates

#### Day42 - [Deep Model] (./Day41-55/02. In-depth model.md)

- Relational database configuration
- Manage the use of the background
- Complete CRUD operations on the model using ORM
- Django model best practices
- Model definition reference

#### Day43 - [Static Resources and Ajax Requests] (./Day41-55/03. Static Resources and Ajax Requests.md)

- Load static resources
- Request data with Ajax request

#### Day44 - [Application of form] (./Day41-55/04. Form application.md)

#### Day45 - [Cookie and Session] (./Day41-55/05.Cookie and Session.md)

#### Day46 - [Application of middleware] (./Day41-55/06. Middleware application.md)

#### Day47 - [Log and Cache] (./Day41-55/07. Log and Cache.md)

#### Day48 - [File upload and rich text editing] (./Day41-55/08. File upload.md)

#### Day49 - [File Download and Report] (./Day41-55/09. File Download and Report.md)

#### Day50 - [Getting Started with RESTful Architecture and DRF] (./Day41-55/10.RESTful Architecture and DRF Getting Started.md)

#### Day51 - [RESTful Architecture and DRF Advanced] (./Day41-55/11.RESTful Architecture and DRF Advanced.md)

#### Day52 - [Use Cache] (./Day41-55/12. Use Cache.md)

#### Day53 - [SMS and Email] (./Day41-55/13. SMS and Email.md)

#### Day54 - [Asynchronous Tasks and Scheduled Tasks] (./Day41-55/14. Asynchronous Tasks and Timed Tasks.md)

#### Day55 - [Unit test and project online] (./Day41-55/15. Unit test and project online.md)

- Project development process and related tools
- Generate non-HTML content
- Project deployment and testing
- Initial tuning of project performance
- Web application security protection


### Day56~60 - [Combat Flask] (./Day56-65)

#### Day56 - [Flask Getting Started] (./Day56-60/01.Flask Getting Started.md)

#### Day57 - [Use of Template] (./Day56-60/02. Use of Template.md)

#### Day58 - [Form processing] (./Day56-60/03. Form processing.md)

#### Day59 - [Database Operations] (./Day56-60/04. Database Operations.md)

#### Day60 - [Project actual combat] (./Day56-60/05. Project combat. md)

### Day61~65 - [Combat Tornado] (./Day61-65)

#### Day61 - [Preliminary knowledge] (./Day61-65/01. Prerequisite knowledge.md)

- concurrent programming
- I/O mode and event driven

#### Day62 - [Tornado Getting Started] (./Day61-65/02.Tornado Getting Started.md)

- Tornado overview
- 5 minutes to get started with Tornado
- Route resolution
- Request processor

#### Day63 - [Asynchronization] (./Day61-65/03. Asynchronized .md)

- use of aiomysql and aioredis

#### Day64 - [Application for WebSocket] (./Day61-65/04.WebSocket application.md)

- Introduction to WebSocket
- WebSocket server-side programming
- WebSocket client programming
- Project: Web chat room

#### Day65 - [Project actual combat] (./Day61-65/05. Project combat. md)

- Pre- and back-end separation development and writing of interface documentation
- Front-end rendering with Vue.js
- Use ECharts for reporting
- Push service using WebSocket

### Day66~75 - [Crawler Development] (./Day66-75)

#### Day66 - [Web crawler and related tools] (./Day66-75/01. Web crawler and related tools.md)

#### Day67 - [Data Acquisition and Analysis] (./Day66-75/02. Data Acquisition and Analysis.md)

#### Day68 - [Storage Data] (./Day66-75/03.Storage Data.md)

#### Day69 - [Concurrent download] (./Day66-75/04. Concurrent download.md)

#### Day70 - [Analyze Dynamic Content] (./Day66-75/05. Analyze Dynamic Content.md)

#### Day71 - [Form interaction and verification code processing] (./Day66-75/06. Form interaction and verification code processing.md)

#### Day72 - [Scrapy Getting Started] (./Day66-75/07.Scrapy Getting Started.md)

#### Day73 - [Scrapy Advanced Application] (./Day66-75/08.Scrapy Advanced Application.md)

#### Day74 - [Scrapy Distributed Implementation] (./Day66-75/09.Scrapy Distributed Implementation.md)

#### Day75 - [Reptile project combat] (./Day66-75/10. Reptile project combat. md)

### Day76~90 - [Data Processing and Machine Learning] (./Day76-90)

#### Day76 - [Machine Learning Basics] (./Day76-90/01. Machine Learning Basics.md)

#### Day77 - [Pandas application] (./Day76-90/02.Pandas application.md)

#### Day78 - [Application of NumPy and SciPy] (./Day76-90/03.NumPy and SciPy application)

#### Day79 - [Matplotlib and Data Visualization] (./Day76-90/04.Matplotlib and Data Visualization)

#### Day80 - [k nearest neighbor (KNN) classification] (./Day76-90/05.k nearest neighbor classification.md)

#### Day81 - [Decision Tree] (./Day76-90/06. Decision Tree.md)

#### Day82 - [Bayesian classification] (./Day76-90/07. Bayesian classification.md)

#### Day83 - [Support Vector Machine (SVM)] (./Day76-90/08. Support Vector Machine.md)

#### Day84 - [K-means clustering] (./Day76-90/09.K-means clustering.md)

#### Day85 - [Regression Analysis](./Day76-90/10.Regression Analysis.md)

#### Day86 - [Getting Started with Big Data Analytics] (./Day76-90/11. Getting Started with Big Data Analytics. md)

#### Day87 - [Big Data Analysis Advanced] (./Day76-90/12. Big Data Analysis Advanced.md)

#### Day88 - [Getting Started with Tensorflow] (./Day76-90/13.Tensorflow Getting Started.md)

#### Day89 - [Tensorflow combat] (./Day76-90/14.Tensorflow combat.md)

#### Day90 - [Recommended System] (./Day76-90/15. Recommended System.md)

### Day91~100 - [Team Project Development] (./Day91-100)

#### Day 91: Team Development and Project Topics

Software process model
   - Classic process model (waterfall model)
     - Feasibility analysis (study done or not), output "feasibility analysis report".
     - Demand analysis (what to study), output of the Requirements Specification and product interface prototype.
     - Outline design and detailed design, output conceptual model diagram, physical model diagram, class diagram, timing diagram, etc.
     - Coding / Testing.
     - Go online / maintenance.
   - Agile Development (Scrum) - Product Owner, Scrum Master, R&D Staff - Sprint
     - Backlog of the product (user story, product prototype).
     - Planning meetings (assessment and budget).
     - Daily development (standing meeting, tomato work method, pair programming, test first, code refactoring...).
     - Fix bugs (problem description, replay steps, testers, assignees).
     - Review meeting (Showcase).
     - Review the meeting (where the current cycle is doing well and not well).

     > Supplement: Agile Software Development Manifesto
     >
     > - **Individual and interactive** Higher than processes and tools
     > - **Working software** is higher than detailed documentation
     > - **Customer cooperation** Higher than contract negotiation
     > - **Response changes** Higher than following plan

    ![](./res/the-daily-scrum-in-the-sprint-cycle.png)

      > Role: Product owner (who decides what to do, who can make a decision), team leader (solve various issues, focus on how to work better, shield external influence on development team), development team (project executive) , specifically for developers and testers).
      >
      > Preparation: Business case and funding, contract, defects, initial product requirements, initial release plan, shareholding, formation team.
      >
      > Agile teams typically have 8-10 people.
      >
      > Workload Estimation: Quantify development tasks, including prototype, logo design, UI design, front-end development, etc., try to decompose each work into a minimum task, the minimum task size is not more than two days, and then estimate the overall project. time. Paste each task on the whiteboard. The whiteboard is divided into three parts: to do (to be completed), in progress (in progress), and done (completed).

2. Project team formation

   - Team composition and role

     > Description: Thank you, Ms. Fu Xiangying for drawing this beautiful company organization chart below.

     ![company_architecture](./res/company_architecture.png)

   - Programming specification and code review (flake8, pylint)

     ![](./res/pylint.png)

   - Some "conventions" in Python (see [Python Conventions - How to Write Pythonic Code]] (Python conventions.md)

   - Reasons that affect the readability of the code:

     - There are too few code comments or no comments
     - Code breaks language best practices
     - Anti-mode programming (spaghetti code, copy-paste programming, vain programming, ...)

3. Introduction to team development tools
   - Version control: Git, Mercury
   - Defect Management: [Gitlab] (https://about.gitlab.com/), [Redmine] (http://www.redmine.org.cn/)
   - Agile closed-loop tools: [Zen Dao] (https://www.zentao.net/), [JIRA] (https://www.atlassian.com/software/jira/features)
   - Continuous integration: [Jenkins] (https://jenkins.io/), [Travis-CI] (https://travis-ci.org/)

   Please refer to ["Team Project Development"] (Day91-100/Team Project Development.md).

##### Project Selection and Understanding Business

1. Scope setting

   - CMS (User Side): News Aggregation Website, Q&A/Share Community, Film Critics/Book Review Website, etc.
   - MIS (client + management): KMS, KPI assessment system, HRS, CRM system, supply chain system, warehouse management system, etc.

   - App background (management + data interface): second-hand transactions, newspapers and magazines, niche e-commerce, news, tourism, social, reading, etc.
   - Other types: self-industry background and work experience, business is easy to understand and control.

2. Requirements understanding, module partitioning and task assignment

   - Understanding of requirements: brainstorming and competing product analysis.
   - Module division: drawing mind map (XMind), each module is a branch node, each specific function is a leaf node (represented by verbs), need to ensure that each leaf node can not regenerate new nodes, determine each The importance, priority, and workload of leaf nodes.
   - Task assignment: The project leader assigns tasks to each team member based on the above indicators.

   ![](./res/requirements_by_xmind.png)

3. Develop a project schedule (updated daily)

   Module | Features | People | Status | Complete | Work Hours | Schedule Start | Actual Start | Plan End | Actual End |
   | ---- | -------- | ------ | -------- | ---- | ---- | -------- | -------- | -------- | -------- | ---------------- |
   | Comments | Add a comment | Wang Da Hammer | Ongoing | 50% | 4 | 2018/8/7 | | 2018/8/7 |
   | | Delete comment | Wang Da hammer | Waiting | 0% | 2 | 2018/8/7 | | 2018/8/7 |
   | | View comments | Bai Yuanfang | Ongoing | 20% | 4 | 2018/8/7 | | 2018/8/7 | | Code review required |
   | | Vote Vote | Bai Yuanfang | Waiting | 0% | 4 | 2018/8/8 | | 2018/8/8 |

#### Day 92: Database Design and OOAD

##### Conceptual Model and Forward Engineering

1. UML (Unified Modeling Language) class diagram

   ![uml](./res/uml-class-diagram.png)

2. Create a table from the model (forward engineering)

   ```Shell
   Python manage.py makemigrations app
   Python manage.py migrate
   ```

##### Physical Model and Reverse Engineering

1. PowerDesigner

   ![](./res/power-designer-pdm.png)

2. Create a model from the data table (reverse engineering)

   ```Shell
   Python manage.py inspectdb > app/models.py
   ```

#### Day 93-98: Using Django Development Project

> Description: For details, please refer to [Django Knowledge Point Overview] (Day91-100/Django Knowledge Point Overview.md)

##### Public issues in project development

1. Database configuration (multi-database, master-slave replication, database routing)
2. Cache configuration (partition cache, key settings, timeout settings, master-slave replication, failure recovery (sentinel))
3. Log configuration
4. Analysis and debugging (Django-Debug-ToolBar)
5. Easy to use Python module (date calculation, image processing, data encryption, tripartite API)

##### REST API Design

1. RESTful architecture
   - [Understanding RESTful Architecture] (http://www.ruanyifeng.com/blog/2011/09/restful.html)
   - [RESTful API Design Guide] (http://www.ruanyifeng.com/blog/2014/05/restful_api.html)
   - [RESTful API Best Practices] (http://www.ruanyifeng.com/blog/2018/10/restful-api-best-practices.html)
2. Writing of the API interface document ([Network API Interface Design]] (Day91-100/Network API Interface Design.md)
   - [RAP2](http://rap2.taobao.org/)
   - [YAPI](http://yapi.demo.qunar.com/)
3. [django-REST-framework] (https://www.django-rest-framework.org/) application

##### Analysis of key difficulties in the project

1. Use cache to ease database stress - Redis
2. Use message queue for decoupling and clipping - Celery + RabbitMQ

#### Day 99-100: Testing and Deployment

##### unit test

1. Type of test
2. Write unit tests (unittest, pytest, nose2, tox, ddt, ...)
3. Test coverage (coverage)

##### Project Deployment

> Description: Please refer to [Project Deployment Online Guide] (Day91-100/Project Deployment Online Guide.md).

1. Preparation before deployment
   - Key settings (SECRET_KEY / DEBUG / ALLOWED_HOSTS / Cache / Database)
   - HTTPS / CSRF_COOKIE_SECUR / SESSION_COOKIE_SECURE
   - Log related configuration
2. Linux common command review
3. Installation and configuration of Linux common services
4. Use of uWSGI/Gunicorn and Nginx
   - Comparison of Gunicorn and uWSGI
     - For simple applications that don't require a lot of customization, Gunicorn is a good choice. The learning curve of uWSGI is much steeper than Gunicorn. Gunicorn's default parameters are already adaptable to most applications.
     - uWSGI supports heterogeneous deployments.
     - Since Nginx itself supports uWSGI, Nginx and uWSGI are generally bundled together online, and uWSGI is a full-featured and highly customized WSGI middleware.
     - In terms of performance, Gunicorn and uWSGI actually perform quite the same.
5. Virtualization Technology (Docker)

##### Performance Testing

> Description: For details, please refer to [Django Knowledge Point Overview] (Day91-100/Django Knowledge Point Overview.md).

1. Use of AB
2. Use of SQLslap
3. Use of sysbench

##### automated test

1. Automate testing with Shell and Python
2. Automate testing with Selenium
   - Selenium IDE
   - Selenium WebDriver
   - Selenium Remote Control
3. Introduction to the test tool Robot Framework

##### Project Performance Tuning

1. Database performance tuning - please refer to ["MySQL related knowledge"] (Day91-100/MySQL related knowledge.md)
   - Software and hardware optimization

   - SQL optimization

   - Architecture optimization

     - Sub-database

     - Master-slave replication, read-write separation
     - Cluster architecture

2. Web server performance optimization

   - Nginx load balancing configuration

   - Keepalived achieves high availability

3. Code performance tuning

   - Multithreading
   - Asynchronization

4. Static resource access optimization
      - Cloud storage
      - CDN



> Acknowledgement: Thanks to my colleagues Gu Yu, Zhang Xu, Xiao Shirong, Wang Haifei, Rong Jiawei, Lu Fengkun and other technical guidance and help.