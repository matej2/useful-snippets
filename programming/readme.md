# Programming resources

[5 Coding projects ideas](https://www.youtube.com/watch?v=n2B-FClr5rA)

[Projects for portfolio](https://www.youtube.com/watch?v=sGw7v-wAQ2s)


## Project structure

The following structure is a good guideline when starting a new project. Note that not all directories are required.

```
backend/
├── src/
│   ├── controllers/         # Request handlers
│   ├── services/            # Business logic
│   ├── repositories/        # Database operations
│   ├── models/              # Data models/entities
│   ├── dtos/                # Data transfer objects
│   ├── interfaces/          # Type/interface definitions
│   ├── middleware/          # Auth, logging, etc.
│   ├── utils/               # Helper functions
│   ├── config/              # Configuration files
│   ├── constants/           # Constant values
│   ├── routes/              # Route definitions
│   ├── validators/          # Validation logic
│   └── app.ts|js            # App entry point
├── tests/
│   ├── unit/                # Unit tests
│   ├── integration/         # Integration tests
│   └── e2e/                 # End-to-end tests
├── migrations/              # Database migrations
├── seeders/                 # Database seed data
├── scripts/                 # Deployment/maintenance scripts
├── .env                     # Environment variables
├── .env.example             # Env template
├── package.json             # Project metadata
├── tsconfig.json            # TypeScript config
└── README.md                # Project documentation
```

## Java links

[Java Full Course + exercises ](https://www.youtube.com/watch?v=xTtL8E4LzTQ)
[Advanced Java Full Course 2023](https://www.youtube.com/watch?v=Ae-r8hsbPUo)
[Hands-on Java - All-in-One Tutorial Series](https://www.youtube.com/watch?v=Ux0Yzedi3Xc)

## Java project setup

[Java Installation for Linux](https://stackoverflow.com/a/76321378)

1. Install Intellij Community edition. Java anv Maven will be installed along with that. In installation, make sure to select Java OpenJDK main version (not early access)

2. Check if environment variable *JAVA_HOME* is set to a installed version of Java. Also check that environment varibale *MAVEN_HOME* is also properly set to Maven installation.

3. Open desired project, go to settings - Build, execution and deployment - Compiler and enable *Enable annotation processing*

4. Go to project home directory, right click on Maven file and select *Add maven project*

## Java Complete guide

[Video link](https://chat.deepseek.com/a/chat/s/ca336740-9064-4f19-afad-7a5689f754d4)

```
⭐️Time Stamps⭐️ 
#2   (00:20:26)  variables ❌   
#3   (00:32:58)  swap two variables 💱
#4   (00:36:42)  user input ⌨️
#5   (00:44:40)  expressions 🧮
#7   (00:55:01)  Math class 📐   
#8   (01:01:08)  random numbers 🎲
#9   (01:05:39)  if statements 🚧
#10 (01:11:51)  switches ⬇
#11 (01:16:36)  logical operators ❗
#12 (01:24:33)  while loop 🔄
#13 (01:28:13)  for loop ➰
#14 (01:32:23)  nested loops ➿
#15 (01:38:28)  arrays 🚗
#16 (01:44:54)  2D arrays 🚚
#17 (01:52:59)  String methods 💬
#18 (01:59:18)  wrapper classes 🎁
#19 (02:06:30)  ArrayList 🧾
#20 (02:11:02)  2D ArrayList 📜
#21 (02:17:35)  for-each loop 🔃
#22 (02:21:20)  methods 📞
#23 (02:32:24)  overloaded methods ☎️
#24 (02:38:03)  printf 🖨️
#25 (02:49:25)  final keyword ⛔
#26 (02:51:24)  objects (OOP) ☕
#27 (03:01:36)  constructors 👷
#28 (03:11:36)  variable scope 🌍
#29 (03:16:39)  overloaded constructors 🍕
#30 (03:24:04)  toString method 🎉
#31 (03:30:08)  array of objects 🍱
#32 (03:35:48)  object passing 🏬
#33 (03:40:27)  static keyword ⚡
#34 (03:48:10)  inheritance 👪
#35 (03:53:45)  method overriding 🙅‍♂️
#36 (03:57:33)  super keyword 🦸‍♂️
#37 (04:05:06)  abstraction 👻
#38 (04:10:01)  access modifiers 🔒
#39 (04:19:39)  encapsulation 💊
#40 (04:27:30)  copy objects 🖨️
#41 (04:34:03)  interface 🦅
#42 (04:41:19)  polymorphism 🏁
#43 (04:46:55)  dynamic polymorphism ✨
#44 (04:55:13)  exception handling ⚠️
#45 (05:02:31)  File class 📁
#46 (05:09:15)  FileWriter (write to a file) 📝
#47 (05:12:30)  FileReader (read a file) 📖
#74 (10:15:14)  generics ❓
#75 (10:36:43)  serialization 🥣
#77 (11:08:36)  threads 🧵
#78 (11:24:01)  multithreading 🧶
#79 (11:38:44)  packages 📦
#80 (11:42:49)  compile/run command prompt 💽
#81 (11:50:51)  executable (.jar) ☕
```

Group 1: Basic Syntax & Control Flow  
Project Idea: Personal Budget Tracker  
- Take user input for income/expenses  
- Use arrays/ArrayLists to store transactions  
- Calculate monthly balance  
- Display spending patterns  
- Simple console UI with switches  

Group 2: OOP Fundamentals  
Project Idea: Library Book Manager  
- Book class with title/author/genre  
- Library class with static book count  
- toString() for book details  
- ArrayList to manage books  
- Optional File I/O  

Group 3: Advanced OOP & File Handling  
Project Idea: Vehicle Rental System  
- Vehicle class hierarchy  
- Rentable interface  
- 2D ArrayList for fleet  
- File I/O for persistence  
- Exception handling  

Group 4: Collections & Generics  
Project Idea: Quiz Application  
- Question class with generics  
- 2D ArrayList for quizzes  
- Score tracking  
- Random question order  

Group 5: Multithreading & Serialization  
Project Idea: Weather Data Fetcher  
- Multithreaded data fetching  
- Data serialization  
- Thread synchronization  
- Performance comparison  

Group 6: Build & Deployment  
Project Idea: Command-Line To-Do List  
- Package structure  
- Command-line execution  
- Executable JAR  
- File persistence