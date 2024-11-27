# Iteration 0 Planning

## The Project Objective

- To build a Massive Open Online Course (MOOC) system.

  This system contains two sub-systems: one is for administrator's management and the other is for users who would register for the on-line courses.

- Bridge the gap for students who are in rural areas and cannot access good quality educational resources

## Development Environment Configuration

- The Login and Role Access-Based Control Module
- The Course Management Module
- The Test Management Module
- The AI-Based Score Module

Front-end:

```bash
   pre-commit hook
   npm create vite@latest
   npm install
   npm install --save-dev husky lint-staged
   npm pkg set scripts.prepare="husky install"
   git init
   npm run prepare
   chmod +x .husky/_/pre-commit
   add .github folder in the root
   add a workflow folder under the .github folder
   add the cy.yml file
```

Back-end:

```dotnet
   create a new ASP.NET project in Visual Studio
   create controller
   create service
   create data model
   install entityframework Nuget package
```

## The Course Content Display Module

## Tech Stack

- Front-end: Vite, React.js, TailwindCSS, MUI, Formik, Axios, Yup, Redux, React Router

- Band-end:.Net 8, EntityFramework 8, AutoFac, AutoMapper,sqlite,redis

- Database: Sqlite, Redis
