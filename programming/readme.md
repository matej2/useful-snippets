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

## Java project setup

1. Install Intellij Community edition. Java anv Maven will be installed along with that. In installation, make sure to select Java OpenJDK main version (not early access)

2. Check if environment variable *JAVA_HOME* is set to a installed version of Java. Also check that environment varibale *MAVEN_HOME* is also properly set to Maven installation.

3. Open desired project, go to settings - Build, execution and deployment - Compiler and enable *Enable annotation processing*

4. Go to project home directory, right click on Maven file and select *Add maven project*