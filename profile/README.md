## Driving School Manager

### Developers:
- Jakub Szymański, 
- Przemysław Frąckowiak-Szymański, 
- Jakub Piecuch

### General app description:
The main purpose of the application is to solve the problem of manual registration for individual driving lessons at a driving school. The solution will be to create a personalized web application for driving schools in the country.

### Technical description: 
**Backend:** Spring Boot REST application. The application meets all the requirements of level 2 of the Richardson Maturity Model. We use tools such as Lombok and MapStruct. We focus on creating clean code and using appropriate design patters, e.g. DTO Pattern.

**Frontend:** Angular Application with PrimeNG Library.

### Tech Stack:
**Backend:**
- Java 17
- Spring Boot 3
- JUnit 5

**DataBase:**
- H2 and/or MySQL for development

**Frontend:**
- Angular 15 

### App features: 

**As Admin:**

- Crud operations on Students,
- Adding hours locks,
- Crud operations on Lessons,
- Dynamic search of Students,
- Browsing, editing and printing information about Students,
- Newsletter – sending messages to clients,
- Generating .pdf files with teachers working hours summary (single, group, historic).

 **As Student:**
 
- Booking lessons (advanced feature consisting of choosing the day, hour, instructor and car, sending a request to an admin and getting confirmation via e-mail),
- Browsing finance history,
- Browsing lessons history,
- Generating .pdf files with particular informations (like payments, lessons etc.),
- Receiving messages via newsletter.

### Version control: 
- system: GIT
- branch naming: Developer signature + “_ft_ + feature short name, eg. “js_ft_addingStudents”
- commit naming: Developer signature + action (feature, fix, change, delete or test) + feature name, eg. “js_fix_addingStudents”
- main branches:
  - main – release app version
  - dev – stable and tested version of application
- workflow: every change requires positive review before merging to dev branch
