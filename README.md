# CS_IA_Aleks TutorFlix web application
![](https://github.com/AleksandarDzudzevic/CS_IA_Aleks/blob/main/Screenshot%202023-09-02%20at%2014.18.57.png)
Fig.1 shows the picture created for TutorFlix using Dream AI[^1] generated on the prompt "Art representing Tutoring services, presenting a tutor and a student".

## 1. [Criteria A: Planning](#criteria-a-planning)

1.1. [Definition of the problem](#problem-definition)

1.2. [Rationale for a proposed solution](#rationale-for-proposed-solution)

1.3. [Design Statement](#design-statement)

1.4. [Success Criteria](#success-criteria)
## 2. [Criteria B: Design](#criteria-b-design)

2.1[System Diagram](#system-diagram)

2.2. [Wireframe Diagram](#wireframe-diagram)

2.3. [ER Diagram](#er-diagram)

2.4. [UML Diagram](#uml-diagram)

2.5. [Flow Diagram](#flow-diagram)

2.6. [Test plan](#test-plan)

2.7. [Record of tasks](#record-of-tasks)

## 3. [Criteria C: Development](#criteria-c-development)

3.1.[Tools and techniques used](#tools-and-techniques-used)

3.2. [Sources](#sources)

3.3[Development](#development)

## 4. [Criteria D: Functionality](#criteria-d-functionality)
 
4.1 [SNS Video](#video-showcase)

## 5. [Criteria E: Evaluation](#criteria-e-evaluation)

5.1 [Table of Evaluation](#evaluation-table)

## 6. [Appendix](#Appendix)
# Criteria A: Planning

## Problem Definition

## Problem Definition
As a student, I often struggled with not having a place to find the right tutor. Just like many, I ended up going with the tutors recommended by friends or relatives, which usually turned out to be better at selling their services than actually teaching and that bothered me. I also struggled with finding ones that lived close to me, and as I usually just got their phone number as a contact, I wasn't aware of who they were and how much they charged. I got contacted by my client, a teacher, who saw a similar issue and explained that in the past he tried using online selling platforms such as eBay or Craigslist to post his advertisement for tutoring services, but was unsuccessful as the students who wanted to find him couldn't due to many other tutors teaching the same subject. Even with less experience, charging too much, and living far away, the number of other advertisements made it impossible for him to find students, even though he was better educated than other tutors which gave him a competitive advantage. To change this, my client requested a web application that would serve as a tutoring platform where students can find tutors that are well-ranked not well-advertised, live close to them, and are within their price range so that tutoring services can finally be level that they are supposed to. Furthermore, this app aims to constantly interact with users establishing a relationship filled with trust, which isn't the case with current platforms which often seem sketchy. This problem definition was established with the help of the data gathered through questionnaires. (referred to in the [appendix](#appendix))



## Rationale for Proposed Solution
To revolutionize tutoring services and allow the best-ranked tutors to get the most exposure, instead of the ones with the best advertising, I have decided to develop a web application for my client that will serve as an inclusive platform that will connect highly ranked tutors and students seeking their help, allowing the most optimal learning experience.

## Design Statement
I will design an innovative web application that will make connecting tutors and students easier. The development will be done using the software Flask framework in Python, CSS, and HTML. It will take around 10 weeks to develop and will be evaluated according to the success criteria stated below by the client.

### Why Web Application?
Web applications are more adequate when developing a platform that offers services like the one I am making because it allows easier access to many different tutors across multiple devices without the need for downloading and installing an application. With a constant addition of new tutors across different subjects, the web application doesn't ask for constant updates. Students who are looking for a tutor can simply access the website through a web browser on their desktop or mobile devices. This increases the potential user number and makes it easier for users to share their experience with tutors with others, allowing high-quality tutors to jump out from the rest. Lastly, web applications can be maintained easily. They can be optimized for search engines, making it easier for new users to discover and join this platform both as tutors and as students, depending on their needs.

### Why Python?
Python contains many versatile features, which make it a better choice compared to other languages, for example, PHP[^2]. Python's Flask framework is ideal for developing a website for a tutoring platform due to its lightweight and flexible nature [^3]. Flask's simplicity and ease of use make it an excellent choice for this project, allowing developers to focus on the website's core features and functionality. It also offers a range of libraries and extensions, making it easier to implement complex features such as authentication and database connectivity, when compared to its competitors such as PHP or ruby [^4]. With Python's object-oriented programming, developers can write code that is easy to read, modify, and maintain. This is essential when creating a complex web application such as a social network website. Additionally, Python has an active community of developers who offer support and resources, making it easier to learn and develop with the language.

### Why SQL?
To store the vast amounts of data needed for an online tutoring platform, a reliable and efficient database is essential. While non-SQL databases can be an option, SQL databases offer several advantages that make them better suited for this purpose. The main advantage of SQL databases is their ability to handle large amounts of data efficiently, thanks to their relational structure[^5]. The relational structure of SQL databases makes it easier to manage and query data, as it is stored in tables. This feature also ensures that data is consistent and accurate, as it is subject to strong data integrity constraints[^6]. With all the data that is being stored for both student and tutor accounts, an SQL database is essential to ensure efficient data handling and management.


## Success Criteria
1) The tutoring platform will have a secure register system, unique for student and tutor accounts with access to different features on the platform.
>[ I often struggled with not having a place to find the right tutor/I usually just got their phone number as a contact]
2) The tutoring platform will contain useful filter options such as search by title, country, subject, and price range.
>[I also struggled with finding ones that lived close to me, and as I usually just got their phone number as a contact, I wasn't aware of who they were and how much they charged]
3) The tutoring platform will allow tutor accounts to upload/delete multiple tutoring posts for different subjects and topics that they offer to teach, all on one account.
>[in the past he tried using online selling platforms such as eBay or Craigslist to post his advertisement for tutoring services, but was unsuccessful]
4) The tutoring platform will have a grading system for tutors and list tutors by highest average grade so that the best-performing ones gain the most exposure.
>[ which usually turned out to be better at selling their services than actually teaching]
5) The tutoring platform will allow students to see all posts by a specific tutor.
>[was unsuccessful as the students that tried to find him couldn't due to many other tutors teaching the same subject.]
6) The web application will have options to communicate with users through email for features such as sending the forgotten password, or information about application updates.
> This app aims to constantly interact with users establishing a relationship filled with trust, which isn't the case with current platforms which often seem sketchy.
# Criteria B: Design
## System Diagram
![](https://github.com/AleksandarDzudzevic/CS_IA_Aleks/blob/main/IA%20System%20DiagramVersionLast.png)
Fig.2 shows the system diagram of the online tutoring platform.
## Wireframe Diagram
![](https://github.com/AleksandarDzudzevic/CS_IA_Aleks/blob/main/Wireframe%20IA.png)
Fig.3 Shows the wireframe diagram 
## ER Diagram
![](https://github.com/AleksandarDzudzevic/CS_IA_Aleks/blob/main/ER%20DIAGRAM_IA_1.png)
Fig.4 Shows the ER diagram of the online tutoring platform, which represents the database structure of the web application
## UML Diagram
![](https://github.com/AleksandarDzudzevic/CS_IA_Aleks/blob/main/UML_IA.png)
Fig. 8 shows the class used for manipulating the database, used for the website application
## Flow Diagram

## Test plan
|Test Number|Description|Test Type| Target|Procedure|Expected Outcome|
|-----------|-----------|--------|-----------|-----------------|----|
|1|Account registration system|Unit testing|Have a fully functional registration system that checks if the proper values are input in the email and password fields|(1) Run app.py (2) Click the register button on the login screen (3) Input a username: TesterSNS, email: testersns@gmail.com, password:abc123! following the password policy, account type: Student and Country: England that will be used for this tester account(4) After filling in all the fields create an account (5) Try to log in with the new account to see if it exists now| After following the procedure, a user should be able to login using the credentials of the newly created account|
|2|Tutor list inspecting from a student account type|Unit testing| Be able to access the tutor list and see all the available tutors and their tutoring posts for different subjects.|(1)Run Project_4.py(2)Login using adequate credentials for the tester account created in test no.1. (3)Choose the "see all tutors" option from the navigation bar.(4)Check if the redirected page shows a table containing the id, username, and country for each tutor| The student is able to access the tutor list from the main menu and will be able to see all the tutorflix tutors| 

|3|Accesing a specific user's profile from the user list|Integration testing| Access a specific user's profile  by choosing it from the user list|(1)Run Project_4.py(2)Login using adequate credentials for the tester account created in the test no.1. (3)Choose the "see all users" option from the navigation bar. (4) Choose a desired user and click on their nickname to get redirected to his profile. (5) Check if his profile and posts  (if there are any) are displayed successfully| A user can choose to view a specific creator profile that he is interested in.|
|4|Finding a specific user through filter options in the user table|Integration testing|Find a user through username search or by choosing a specific city of interest |(1)Run Project_4.py(2)Login using adequate credentials for the tester account created int test no.1. (3)Choose the "see all users" option from the navigation bar. (4) Choose a city and see if only users from that city appear in the user table. (5) Now type a certain username or a part of it and see if only adequate users appear | Both filter functions work and are properly integrated with the user table database and main menu|
|5|Code practices around HTML and Python, regarding usage of loops and their nesting  |Code Review| Replace repeating functions and features using better coding practices by using loops, and make the code more efficient by nesting loops.|(1) Review Project_4.py python code and HTML code to see any repetitive parts. (2) Create an algorithm that would replace the repetitive part using loops and nesting them if necessary. (3) Replace the old repetitive code and connect new algorithm and HTML code to the main SNS code | The code now uses loops for the profile accessing and for the learn about city feature.| 
|6| Commenting on complex code practices |Code Review| Adding comments that would explain the usage of more complex programming tools and algorithms to help future potential developers| (1) Review the python Project_4.py code and focus on the more complex algorithms and routes that have unique features (2) Add a comment explaining their usage and function in the code| The code is easier to understand and is more open for future co-development|


## Record of Tasks
| Task No | Planned Action                                              | Planned Outcome                                                                                                 | Time estimate | Target completion date | Criterion |
|---------|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
|1|Write problem definition (Planning)|Have a clear problem that states the issue, its consequences, and a clear approach and solution that is being proposed| 20 min |8.7.2023 |A | 
|2|First client meeting: success criteria and required information (Planning)|Have a first client meeting and get the client to state the success criteria and basic information needed to establish a design statement and rationale for the solution that will be proposed to the client | 30 min|10.7.2023 |A |
|3|Write the first version of the rationale for the proposed solution and design statement (Planning)|Write down the rationale and design statement that will be presented to the client |35 min |10.7.2023 |A |
|4| Rewrite rationale for the proposed solution (Planning| Rewrite design statement so that it better explains methodology and tools that will be used for this web application development| 15 min | 11.7.2023| A|
|5| Design first version of the System diagram (Design)| Have the system diagram of the web application finsihed|20 min | 13.7.2023| B| 
|6| Add table of content (Planning)	 | Add table of content at the top of the file that will allow easier inspection of the project| 15 min|13.7.2023 | A|
|7| Construct the first version of database structures needed for the web application (Design)| Have the sketch of the databases for the initial idea of how the web application will be structured| 30 min| 14.7.2023|B|
|8|Design first version of the ER diagram (Design)| Design the first version of the diagram representing the Data structure of the web application| 25 min|20.7.2023 | B|
|9| Create databases and start with the program development (Development)|Start coding the web application and create databases  |45 min | 21.7.2023|C |
|10| Design the web applications logo and its color panel with the help of the client (see in [appendix](#appendix)) (Design)|Design the logo that would be used on the client's web application and the colors that will dictate the template|30 min|23.7.2023|B |
|11|Create the first version of the wireframe diagram of the web application| Have a clear visual representation of the web application's structure and interconnectivity between its features|23.7.2023||
|12| Create the first version of the login and registration system |Create a functional login/registration system |1 h|30.7.2023 |C|
|13| Design second version of the System diagram (Design)| Have the system diagram showcase both client and server device|20 min | 15.8.2023| B| 
|14|Connect login/registration to the database (Developing)|Established connection now add/checks newly registered/ already existing accounts to/with the data database|20 min| 23.8.2023|C|
|15| Redo Login and Register UI to match the general template used for the web application | Make the registration system UI fit better into the web app style. | 20 min| 1.9.2023 | C|
|16| Add password policy and create an interactive response to the user's input for the password. |Make a password policy and add an emoji reaction showing if the user followed the policy. | 25 min|16.9.2023 | C|
|17| Add JWT token in order to improve web app security and only allow feature access to logged-in users | Only registered users can access the application features| 30 min | 21.9.2023| C|
|18| Create the UML diagram for the web application |Create the UML diagram for the class used for manipulating databases for the web application | 20 min|26.9.2023 | B|
|19| Update the wireframe diagram so that it shows the new design of the web application|Have the wireframe diagram show an accurate version of the web application|20 min |28.9.2023 | B |
|20|  Perform 2 unit tests explained in the test plan section (Testing)  | Perform tests of the registration system and the tutor list feature  |  15 min | 6.10.2023  |  B   |
|21| Test accessing the tutors list from the main menu page (Testing) | Update the test plan with integration test relating to allowing registered students to access the table containing tutors of tutorflix| 15 min  |   6.10.2023 | B    |
|22| Test accessing a specific tutor from the user list feature. (Testing) | Update the test plan with an integration test relating to the feature that checks a specific tutor account from the tutor list  |  15 min |  8.10.2023  |  B   |
|
|23| | | | | |
|24| | | | | |
|25| | | | | |
|26| | | | | |
|27| | | | | |
|28 | Run code review testing for potential loops and loop nesting and see if any complex algorithms used need a comment to explain them to potential co-developers (Testing) | Have a more efficient code of higher quality and better coding practices that would make future co-development easier  | 25 min   | 1.11.2023|  B   |

# Criteria C: Development
## Tools and techniques used
## Sources
## Development

# Criteria D: Functionality
## Video showcase

# Criteria E: Evaluation
## Evaluation table
|Criteria number| Criteria| Final product| Criteria success|
|---------------|----------|-------------------------------|--------------|

## Client interview

## Recommendation


# Appendix
![](https://github.com/AleksandarDzudzevic/CS_IA_Aleks/blob/main/client_interview_1st.png)

### The first client consultation was done remotely on July 10th, 2023 13:15 pm, during which success criteria were established.

[^1]: Dream AI prompt: "Art representing Tutoring services, presenting a tutor and a student". 6 July 2023 https://dream.ai/create
[^2]: Sengar, Ritesh. “Python vs PHP: Which Is Better for Web Development?” Hackernoon, 7 Jan. 2021, hackernoon.com/python-vs-php-which-is-better-for-web-development-cj1236mj. 
[^3]: "Welcome to Flask." Flask Documentation, 15 Jan. 2023, flask.palletsprojects.com/en/2.1.x/. 
[^4]: Grinberg, Miguel. Flask Web Development: Developing Web Applications with Python. 2nd ed., O'Reilly Media, Inc., 2018. 
[^5]: “What Is a Database?” Oracle, https://www.oracle.com/database/what-is-database/. 
[^6]: "What is SQL?" W3Schools, W3Schools, https://www.w3schools.com/sql/
[^7]: https://www.smashingmagazine.com/2010/01/color-theory-for-designers-part-1-the-meaning-of-color/
[^8]: 4. Auth0. “JSON Web Tokens.” Auth0 Docs, https://auth0.com/docs/secure/tokens/json-web-tokens. 
