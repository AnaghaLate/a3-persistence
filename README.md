Assignment 3 - Persistence: Two-tier Web Application with Flat File Database, Express server, and CSS template
===

Due: September 16th, by 11:59 AM.

This assignnment continues where we left off, extending it to use the most popular Node.js server framework (express), a flat file database suitable for small applications (lowdb), and a CSS application framework / template of your choice (Boostrap, Material Design, Semantic UI, Pure etc.)

## Hotel Casa Anagha

https://a3-anaghalate.glitch.me

The goal of the application is a hotel reservation site, a continuation of my last project. During this project, I had the most difficulty with incorporating the middleware packages. For authentication I used Passport and used LowDb for my database simply since they were the easiest and since it was briefly gone over in class. I used Sanitize.cc for my framework since I deemed it one that would give me the most flexibility to explore the CSS. The 5 middlewares are as follows : Passport (authentication) , Helmet (setting of HTTP Requests) , Morgan (logging of HTTP Requests) , and NodepStatsd and Response-Time (collection of response times). 


## Technical Achievements
- **Error Handling**: If authentication fields are left blank, then the user will not be able to log in

### Design/Evaluation Achievements
- **Additional Framework**: I used another framework , known as typography.css
