# CSCI-395.48 - Practical Web Development <br/> Spring 2024, Hunter College

---

# Final Project Description & Outline

## Description/Overview

For your final project, you will be creating a **FULL STACK** web application that will integrate with at least **ONE** third party API (PokeAPI, Kanye Rest, etc...) on the internet and be able to perform **C.R.U.D** operations with it. You will also be required to implement data persistency by connecting your app to a database/storage of some sort (writing to file system, local DBs, web services, etc...). Lastly, you will also give a presentation (in person) on your final project, describing what your web app does, outlining the technologies used, your implementation, challenges etc...

Unlike your assignments, for the final project, you are **HIGHLY ENCOURAGED** to work in groups! You will also be presenting as a group and each member of the group is required to contribute to the presentation, focusing on which part of the project they worked on.

---
##  Requirements

This project is designed to help you further practice all the technologies/frameworks/concepts that we've covered in our lectures. As such, you are highly encouraged to use the below technologies/frameworks:

### Core Technology Requirements
Your app **SHOULD** be centered around these two core JS frameworks, as they cover a lot of the core concepts in our course.
1. ReactJS - To build out your frontend HTML/CSS/JS pages.
2. ExpressJS - To build out your backend services that will be running on the server.

You are definitely free to write vanilla HTML/CSS/JS to build out your front/back ends, but it is highly recommended that you use these frameworks!

### Additional (Optional) Technology Requirements
Additional frameworks/technologies that you should consider using for your project to achieve some of the requirements!

1. ReduxJS - If you want to implement a single state for your application.
2. NextJS/React-Router - If you want client side routing for your app.
3. node-fetch/Axios - For fetching data on your backend service.
4. Any CSS/styling/component libraries (Tailwind CSS, Material UI, LESS/SASS, etc...)
5. Redis/Firebase/MongoDB - these are useful for data persistencies/storage.

### API Integration Requirements

You're required to integrate to at least **ONE** API on the internet, by performing at least **ONE** HTTP request against it, either from your frontend ReactJS code, or from your backend ExpressJS service. Below are a few suggestions/resources for fun and interesting APIs to integrate with:

https://apilist.fun/ - List of fun APIs.

https://rapidapi.com/hub - Another list of interesting APIs to work with.

https://thecatapi.com/ - Cats are always beloved on the internet.

https://pokeapi.co/ -  A Pokemon API to give you data about everything Pokemon!

These are just a few of the **PUBLIC** APIs that you can integrate with. You are more than welcome to integrate with other APIs that require you to sign up for a developer account/generate an API key!

### Group Structure/Requirements
You are encourage to work in groups for the final project (although you're welcome to fly solo on this!). Groups should be between 2-5 members each. Each member of the group is also required to contribute to the final presentation, speaking on what the component of the project that they focused on.

---
## Grading Rubric

### Frontend - 30%
- ReactJS is used for frontend.
- Pages render properly and layout is clear.
- Styling/CSS is done properly.

### Backend - 30%
- ExpressJS service is used for the backend service.
- Routes are clearly defined and request/response is handled properly.
- Error handling is handled for the service, it should minimize crashing.

### API Integration - 25%
- Integrates with an API on the web.
- Performs at least **ONE** HTTP request to the API
- Accounts for error handling (i.e API is down, gets error response, etc...)

### Data Persistency - 5%
- Application is able to store data data (either from user or API).
- Data is persisted in some form, when application restarts.
- Read/write data from/to a datasource.

### Presentation - 10%
- A minimum of 5min per group member, minimum of 10min for each project.
- **EVERY** group member should participate in presenting, speaking on what they worked on/contributed to the project.
- Also included, a short demo of your app and how it works.
- Lastly, there will be a short Q&A section at the end to answer any questions from the class/audience.

---
## Proposal Outline (Submit On Blackboard!)

Submit a document (Google Doc, MS Word, PDF, etc...) on Blackboard, addressing the below points:

### 1. Project Title/Group Members
- In the document header/top of the page, include the name of your project.
- Also list out your group member names.

### 2. Project Description
- A short summary/paragraph outlining your project, something I can glance over really quick to get a sense of what your project is about.
- Perhaps also include a high level overview/architecture diagram of how your app should function.

### 3. Technical Overview
- Go over the technologies/frameworks/libraries that you plan to use.
- Go into detail how you plan to integrate these into the app, which component of the app will be implement by what technology, etc...

### 4. API Integration
- Go over the API you plan to integrate with.
- Include a link to it, and a short summary of what it does.
- Include HTTP requests you plan to make against it (at least one!)

### 5. Running The App & Data Persistency
- In this section, speak about how you would set up/start up the app.
- How you plan to introduce data persistency for the application.